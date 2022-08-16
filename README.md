# Plus-Linux 0.4.0
A small project I'm working on idk 

It's based on the latest Kernel at the moment (5.19.1) at a small size. 
It also uses busybox instead of GNU. I may make my own coreutils in C later to make it even smaller and less with bloat. 

*Plus Linux is really buggy because it's still in Alpha*

you can run it using qemu:
```
qemu-system-i386 -fda PlusLinux.img -m 512 -enable-kvm
```

**It's important to be in the same directory as the .img file to be able to boot.
By enableing kvm can show some errors because I didnt put a good tty log daemon in yet.**

If you just run 
```
qemu-system-i386 -fda PlusLinux.img -m 512
```
it can fix it for 70%. I don't know why :/

# Getting Qemu

Debian based Distros:
```
sudo apt update && sudo apt install qemu qemu-kvm
```

Arch based Distros:
```
sudo pacman -S qemu-full
``` 

Fedora based Distros:
```
su -c "yum install qemu"
```
