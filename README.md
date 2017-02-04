#GT-S5360_Kernel_GB_Opensource_Update4

##How to build bcm21553 kernel

Basic knowledge of Linux and compiling is required to be able to build a kernel. You need Linux machine with git and toolchain installed.

##Setup build environment

In your home directory (~/) create the directories:

Open a terminal

     $ mkdir kernel
     $ cd kernel

Building a directory structure that will help keep us organized. The "mkdir" command creates a directory, and the "cd" command moves you into that directory.
The directory structure is complete. Now, you are ready to clone kernel code.

##Setting up repositories

Clone the main kernel repository, run this line in your terminal window:

    $ git clone https://github.com/mohammad92/GT-S5360_Kernel_GB_Opensource_Update4

##Toolchains

    $ git clone https://android.googlesource.com/platform/prebuilts/gcc/linux-x86/arm/arm-eabi-4.4.3

##Building

Open a terminal and type:

    $ cd GT-S5360_Kernel_GB_Opensource_Update4
    $ ./menu

---
bcm21553 kernel menu will appear

> bcm21553-common kernel build script
 
> b- build                           # type b will go to build menu.

> c- clean                           # type c will clean kernel directory.


> r- restart script                  # type r will restart menu.

> x- exit script                     # type x will exit menu.

---

###zImage will be coppied to ~/kernel directory if kernel successfully built.
