# NTR

# TODO LIST

1. The printf impl. (xprintf.c) is not thread-safe, it should be replaced with a thread-safe one.
2. ~~Fix warnings.~~ **(WARNINGS HAVE BEEN REMOVED! YAY!)**

# Compilation using Visual Studio

1. `git clone`
2. Open Visual Studio SLN file.
3. CTRL+SHIFT+B to start Build. By default, it uses `make build`.
4. Look at the Output tab for NMake messages. 
5. Done.

# Supported Make Targets

* Default targets: `make`, `make build`, `make clean`
* For old_3ds payloads: `make old_3ds`
* For new_3ds payloads: `make new_3ds`
* For both payloads: `make both`

# CREDITS

* cell9 - For creating the NTR. What it's called, I don't know yet.
* Reisyukaku - For organizing some certain unknowns in the codebase, making it easier for me to work with.
* WinterMute - For fixing the Makefile. This is an important one, lest we go barbarian on Python script builds again.
* enler - For questioning certain compilation flags, and helping us improve the Makefile.
* For showing me what `uintptr_t`, `volatile`, the meaning of those two together, and teaching me what a broken C project really is, and why it is considered broken:
  * fincs
  * profi200
  * WinterMute
  * thexyz
  * plutoo
  * booto 
  * cpajuste 
  * mtheall 
  * grutezkop

# LICENSE 

GPLv2
