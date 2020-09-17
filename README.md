# GNU GCC Toolchain

Bleeding edge GNU GCC toolchains built from sources with latest binutils and glibc.

## Getting the toolchain

Clone using git 
```
$ git clone https://github.com/theradcolor/arm-linux-gnueabi.git --depth=1
```

> Note: This is continous updating repository made from the latest GNU's GCC sources rather than stable releases, so if you want to use the stable release of gcc clone the stable-gcc branch of this repository

For stable gcc
```
$ git clone https://github.com/theradcolor/arm-linux-gnueabi.git -b stable-gcc --depth=1
```

For ARM64, checkout https://github.com/theradcolor/aarch64-linux-gnu.git

For x86_64, checkout https://github.com/theradcolor/x86_64-linux-gnu.git

## Using the toolchain

Export the `CROSS_COMPILE_ARM32` in enviroment

```
$ export CROSS_COMPILE_ARM32=<toolchain-path>/bin/arm-linux-gnueabi-
```

## License

The GNU Compiler Collection is free software.  See the files whose
names start with COPYING for copying permission.  The manuals, and
some of the runtime libraries, are under different terms; see the
individual source files for details.

GCC is licensed under version 3 of the [GNU General Public License.](https://www.gnu.org/licenses/gpl-3.0.html)

The GCC runtime exception permits compilation of proprietary and free software programs with GCC and usage of free software plugins. The availability of this exception does not imply any general presumption that third-party software is unaffected by the copyleft requirements of the license of GCC. 