# pintos
My take on pintos OS

# The source files 
obtained from git through official pintos git URL ```git://pintos-os.org/pintos-anon```

# Setup for Windows 10

### What I tried but it failed :

~~I downloaded an Ubuntu 18.04 VM .ova with everything packaged and ready for PintOS.~~

~~https://courses.mpi-sws.org/os-ws19/assignments/resources/pintos.ova~~

~~Launched the VM with VMware Workstation Player 16~~

### What I ended up doing :

* WSL on my Win10 machine with an Ubuntu-18.04
* install QEMU and link it :
  * ```sudo apt-get install qemu```
  * ```sudo ln -s /usr/bin/qemu-system-i386 /usr/bin/qemu```
* install make ```sudo apt install make```
* install THE PROPER VERSION OF GCC (Else the first pintos build with ```make``` will fail) ```sudo apt-get install libc6-dev g++ gcc```
* Everyting's good ! You can follow the rest of the pintos docs !

# pintos documentations

Lots of usefuls information on https://courses.mpi-sws.org/os-ws19/assignments/pintos/pintos_1.html
