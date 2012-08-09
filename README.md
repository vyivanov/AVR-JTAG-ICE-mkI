## Atmel JTAG ICE mkI clone ##

![](https://dl.dropbox.com/u/14947871/pics/projects/AVR-JTAG-ICE-mkI-clone.JPG)

### Description ###

This device is a simple implementation of [Atmel JTAG ICE](http://www.atmel.com/Images/doc2475.pdf) clone. [Original source](http://pol-sem.narod.ru/AVRminiICE/jtag.htm).

In schematic author made mistake that explained in article, but schematic image was not fixed. I tried to communicate with him, but did not get response. In any case, my schematic is correct. Besides, I used USB 2.0 interface (FT232 IC) instead of RS-232 for communicating with PC.

There are three LEDs on case:

    * Red    (solid)    Power is on (USB plugged in)
    * Green  (blink)    Data is being transmitted to target (debug) device
    * Yellow (blink)    Data is being received from target (debug) device

### Repository Content ###

    datasheets/                         Datasheets of essential ICs
    eagle/                              PCB design files (Eagle 6 CAD)
    eagle/JTAG-ICE-mkI-clone.eps        Layout for PCB manufacturing
    case-sticker.svg                    Sticker image for case
    firmware.hex                        Firmware for burning to MCU
    README.md                           This file

### Using ###

Instruction of assembling and setting is can found in [original source](http://pol-sem.narod.ru/AVRminiICE/jtag.htm).