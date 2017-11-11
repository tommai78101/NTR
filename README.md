# NTR

# TODO LIST

1. The printf impl. (xprintf.c) is not thread-safe, it should be replaced with a thread-safe one.
2. Fix warnings.

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

# LICENSE 

GPLv2
