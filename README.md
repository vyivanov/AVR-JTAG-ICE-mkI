## Atmel JTAG ICE mkI clone ##

### Description ###

This device is a simple implementation of [Atmel JTAG ICE](http://www.atmel.com/Images/doc2475.pdf) clone. [Original source](http://pol-sem.narod.ru/AVRminiICE/jtag.htm).

In schematic author made mistake that explained in article, but schematic image was not fixed. I tried to communicate with him, but did not get response. In any case, my schematic is correct. Besides, I used USB 2.0 interface (FT232 IC) instead of RS-232 for communicating with PC.

### Repository Content ###

    ./eagle                     PCB design files (Eagle 6 CAD)
    ./eagle/JTAG-ICE-mkI.eps    Layout for PCB manufacturing
    ./case_sticker.svg          Sticker image for case
    ./firmware.hex              Firmware for burning to MCU
    ./README.md                 This file

### Using ###

Instruction of assembling and setting is can found in [original source](http://pol-sem.narod.ru/AVRminiICE/jtag.htm).