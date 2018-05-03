## GNU ARM Embedded Toolchain for Linux/ARM64

This toolchain is for Linux on ARM64 (AArch64) based platforms (compiled and tested on Odroid C2).

Commands:

```
cd gcc-arm-none-eabi-X-YYYY-qQ-major
./install-sources.sh
./build-prerequisites.sh --skip_steps=mingw32
./build-toolchain.sh --skip_steps=mingw32,mingw32-gdb-with-python
```

Oficial source code and binaries (i386, AMD64) are available on:

https://developer.arm.com/open-source/gnu-toolchain/gnu-rm/downloads
