# Plus-Linux 1.0

> Plus Linux is based on Kernel 5.15.127 (LTS) at a small size.   
> It also uses busybox instead of GNU. I may make my own coreutils in C later to make it even smaller and with less bloat.

## What it offers:
1. Main:
    - Plus Linux is based on Kernel 5.15.127
    - It's using Busybox as the systemutils
    - With that it is complete GNU and Systemd free
2. Goals:
    - To fit on a single floppy drive (1.44Mb)
    - Having less bloat than other distros like U*untu
    - Trying to be stable

## Features:
- Plus Linux is so bare bones that you cannot move files with mv. To save space you can use cp and rm for this use.
- Did I already mention that it can run on anything? Try running it on your 23 year old IBM NetVista from the year 2000 ;)
- Darkmode by default!
- Manage your Computer when you messed something up. Mount and unmount drivers or delete your friends nice images he downloaded of 4chan!
- Expandable! Get a second floppy and put something small on it like suckless software which is only a few kilobytes in size! With that you have a ful Linux system on two floppydisks supporting graphics and webbrowsing! 

## A screenshot of Plus Linux
![Plus-Linux-Screenshot](https://github.com/plastic-bottleneck/Plus-Linux/blob/main/src/Plus-Linux.png)

## How to run it in a VM
You can run it using qemu:
```
qemu-system-i386 -fda plus.img
```
---

> Made by Paul alias Plastic Bottleneck GitHub: https://github.com/plastic-bottleneck  
> Check out my custom BASH config: https://github.com/plastic-bottleneck/bashrc
