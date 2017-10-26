# Software

This project mostly builds on the [wii-ext-to-usb](https://code.google.com/archive/p/wii-ext-to-usb/) project.  I took the code provided by that project and added the following:

- Switch communication (I2C) line between the two nunchuks
- Low-pass filter accelerometer values
- Convert accelerometer output to pitch and roll angles

My only changes to the source are in main.c and the name in usbconfig.h

I brought all the files into AVR Studio and set it to use the Makefile provided by the wii-to-ext Project.
