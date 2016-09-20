The hex file contained in this folder is used on all Explore Embedded Atmega32 boards like the Starter AVR
oneMicro Atmega32 etc.

* Flash the hex file to the controller first
* Set the following fuse bits after that
* low_fuses=0xff
* high_fuses=0xde
* lock_bits=0x0F

If fuse bits are not set properly, the controller may get damaged. Proceed with caution
The baud rate for programming is 19200.

