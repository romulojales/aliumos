# AliumOS - Just another Operating System

Alium means other in Latin.


## Objectives

* x86_64
* Raspeberry PI
* UEFI
* Preemptive kernel
* Port python
* GUI, probably using GTK

## Roadmap

1. Classical bootloader via BIOS
2. 16 Bits ping
3. Change to 32 bits
4. Change to 64 bits
5. Change to UEFI
6. Re plan... 

## Test

* Qemu primarily
* One disk, with all the partitions well defined and known.

I don't want to write an OS that will run in any x86_64 computer or disk configuration. Resrincting the target I can focus in the happy path to create an operating system. Later, I can generalize and deal with the corner cases. 
