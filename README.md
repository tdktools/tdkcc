# tdkcc

This project contains source code of TDK cross compilers. This archive of source is the source that are used to built out TDK cross compilers used in TDK toolskit of Phoenix Technologies.

TDK cross compilres are GCC cross compiler toolchains built using crosstool-ng tool on x86-64 Ubuntu Linux. They are canadian cross compiler toolchains that runs on i686 Windows to built output targeting AArch64 Linux platform.

 * Build Machine: x86-64-pc-linux Ubuntu 18.04
 * Host Machine: i686-w64-mingw32
 * Target Machine: aarch64-unknows-linux

The configuration of built TDK cross compiler toolchains is:
 * gcc - 9.3  - the compiler
 * binutils - 2.34  - accessory tools
 * glibc - 2.31  - a 3rd party C library
 * linux - 5.10.100 – part of Linux kernel source 

For more information of how to built out TDK cross compilers, please refer to TDKCrossCompilerArm64.docx.
