# tdkcc
TDK cross compilers used in TDK toolskit of Phoenix Technologies.

This project contains source code of TDK cross compilers. This archive of source is the source that are used to built out TDK cross compilers used in TDK toolskit of Phoenix Technologies.

TDK cross compilres are Canadian cross compiler toolchains built using crosstool-ng tool.
The machines is:
Build: x86_64-pc-linux Ubuntu 18.04
Host: i686-w64-mingw32
Target: aarch64-unknown-linux-gnu

The configuration of built TDK cross compiler toolchains is:
 * gcc - 9.3  - the compiler
 * binutils - 2.34  - accessory tools
 * glibc - 2.31  - a 3rd party C library
 * linux - 5.10.100 – part of Linux kernel source 

For more information, please refer to TDKCrossCompilerArm64.docx
