# PwnPi-A.L.O.A-OLED-build
======================================================================
![pwnpi](https://github.com/beigeworm/PwnPi-A.L.O.A-OLED-build/assets/93350544/a63c79e8-6ab7-4907-bed0-55f05df03062)

**A useful instruction guide for building a complete PwnPi A.L.O.A with OLED screen.**
------------------------------------------------------------------------
you can connect to USB on a target machine using the integrated connector or using the microUSB port closest to the mini-HDMI port on the side of the Pi.
you can power the Pwnpi from the integrated USB connection however, it cannot charge the internal battery this can only be done using the microUSB port at the rear of the device.

***ONLY use this project for EDUCATIONAL PURPOSES.***

This project is based on:
--------------------------------------------------------------------------
https://github.com/RoganDawes/P4wnP1_aloa
**using this project for the OLED:**
https://github.com/beboxos/P4wnP1_ALOA_OLED_MENU_V2

# CONTENTS
---------------------------------------------------------------------------
1. Shopping List
2. Build Process
3. Setting Up
---------------------------------------------------------------------------

# Shopping list
A Raspberry Pi Zero W (with GPIO Header) *not Zero2*

A Waveshare 1.3 inch SPI OLED Display 128x64 pixel
> https://www.aliexpress.com/item/1005003575175230.html

A 3.7V 400mAh Lithium Polymer Li-ion Li-Po Rechargeable Battery
> https://www.aliexpress.com/item/1005005412971611.html

A 3.7V Lithium Battery Charger Protection Board
> https://www.aliexpress.com/item/1005001651603549.html

A Toy switch 1P2T ON-OFF Toggle Switch                          
> https://www.aliexpress.com/item/4000108839457.html

A USB 2.0 3.0 Male A Type USB PCB Connector Plug
> https://www.aliexpress.com/item/1005005242362610.html

# Build Process

**3D printing the shell**
Use the stl files to create a .gcode file for the printer.

You will also need a soldering iron with the necessary materials

some thin guage wire

Hot Glue and Glue Gun

And some superglue..

Now you have all the parts needed, you can start.

**Wiring The components**
The Pi to USB Connection is wired this way. however we will need the power and ground pads for the battery circuit. 

*Example Pi connections*
![pi zero connections](https://github.com/beigeworm/PwnPi-A.L.O.A-OLED-build/assets/93350544/bcd37e6b-703c-44ed-a7fd-41443321f5f7)
*Example USB-A Male Connections*
![usb pin config](https://github.com/beigeworm/PwnPi-A.L.O.A-OLED-build/assets/93350544/774ecdb3-0cae-427a-a515-564bf327376c)

This is the wiring diagram for the complete setup.
---------------------------------------------------------------
*Wiring diagram for the PwnPi OLED*
![pwnpi wiring](https://github.com/beigeworm/PwnPi-A.L.O.A-OLED-build/assets/93350544/6bbbe1c1-cf29-4079-9d14-39eb79de04ec)

# Setting Up

----------------------------------------------
download a pre compliled image below. (This has a few extra Features and HID scripts)

MEGA LINK - [(PwnPi Pre-Compiled Image)](https://mega.nz/file/NKM1ADhA#GfjLaQDG3jB-ZaelmY2fpgAcOww2rvMk4XxPc_uo8h0)

Use rufus to flash the image to an SD card (You dont need to unzip the file before flashing)
----------------------------------------------
the SD card should be at least 16GB in size.

Assemble the parts in the base and hot glue the switch down and the USB-A connector

Glue the battery and charging board to the underside of the screen 
(the USB Micro connector should be centered flush to the edge of the screen board underneath the 3 buttons on top)

Glue down the lid with superglue and leave to dry..

Insert the SD card and now you have a working PwnPi OLED!

==================================================
# If you like my work please leave a star. ⭐
