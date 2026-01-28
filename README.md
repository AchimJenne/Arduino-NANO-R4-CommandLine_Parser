# Arduino-NANO-R4-CommandLine_Parser
Arduino: Nano-R4CommandLine_Parser

A simple ASCII commandline- interface (CLI) with SD-Card File- functions and comfort. Supports VT100-Terminal emulation (like TeraTerm, PUTTY, GTKTerm and other) on the USB-Port.
This project keeps a set of helpful functions for the Arduino NANO-R4 with SD-Card.
![IMG_0578_comp](https://github.com/user-attachments/assets/54898bd9-174e-4ba1-9f40-50ecfe74a7fa)
Picture shows an UNO-R4 minima with SD-Card, Battery bufferd RTC, BME680 and 20x4 LCD on I2C- bus.
The NANO-R4 will work in the the same hardeware envirement

The software supports the CPU internal RTC function and 4ticks/sec callback function for real-time applications.
The NANO-R4 is clocked by a Quarz reference and the CPU-RTC is working well - as better as the UNO-R4 CPU-RTC!
In an equal form there is a 100 Hz GPT- Timer running with own callback.

**AUTO** - shows the ADC 0-3 voltage (Average of 10 measurements)

**CD**, **MD**, **RD** - directory handling

**CONFIG** - shows the SPI- configuration

**COPY** - copy a file from => to filename

**DEL** - removing file 

**DIR** - shows the directory

**DATE** and **TIME** - get and set time/date value

**TYPE** - list an ASCII-File on your terminal

**CLS** - clear the VT100 screen and set the cursor position top-left

**TEMP** - not implemented

**VER** - shows some software informations

**VOL** - list the SD-Card information

**XREC** - XModem-CRC upload to uC uC SD-Card

**XTRAN** - XModem download from uC uC SD-Card

**YREC** - YMODEM-1K CRC upload to uC SD-Card (multible file transfer is possible)

Needed:
-	the SD-Card library must be available

YModem transfer reached up to 23 kByte/s in my tests and the XModem can should transfer 6-10 kByte/s

