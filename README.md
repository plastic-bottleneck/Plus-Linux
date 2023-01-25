# Plus-Linux 0.4.0

Plus Linux is based on Kernel 5.19.1 at a small size. 
It also uses busybox instead of GNU. I may make my own coreutils in C later to make it even smaller and with less bloat. 

*Plus Linux is really buggy because it's still in Alpha*

---

## What it offers:
1. Main:
    - Plus Linux is based on Kernel 5.19.1 (Will be updated soon)
    - It's using Busybox as the systemutils
    - With that it is complete GNU and Systemd free
2. Goals:
    - To fit on a single floppy drive (1.44Mb)
    - Having less bloat than other distros like U*untu
    - Trying to be stable (even though it isn't at the moment)

---

## A screenshot of Plus Linux 0.4.0
![Plus-Linux-Screenshot](https://github.com/plastic-bottleneck/Plus-Linux/blob/main/Images/Plus-Linux-0.4.0.jpg)

---

## How to run it in a VM
You can run it using qemu:
```
qemu-system-i386 -fda PlusLinux.img -m 512 -enable-kvm
```
Important is, that you are in the ```root directory```  of this pull to be able to run it over qemu.  

---

> Made by Paul alias Plastic Bottleneck GitHub: https://github.com/plastic-bottleneck  
> Check out my custom BASH config: https://github.com/plastic-bottleneck/bashrc
