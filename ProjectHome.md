# SDR MK1 Software Defined Radio Firmware #

This is the repository for the SDR MK1 Software Defined Radio firmware. The MK1 is based on the Atmel AT90USB1287 microcontroller and LM97593 DRC chipset from National Semiconductor.
The firmware is using the excellent [LUFA library](http://www.fourwalledcubicle.com/LUFA.php) from Dean Camera for communicating through USB.

Please note, that in order to be able to upgrade the firmware, you will need:

  * [Atmel FLIP utility](http://www.atmel.com/dyn/products/tools_card.asp?tool_id=3886) together with the included USB driver.

Please refer the [Firmware Upgrade Instructions Wiki page](http://code.google.com/p/sdr-mk1/wiki/FwUpgrade) for how to perform the upgrade.

In order to work on source code, you will need:

  * [AVR studio 4](http://www.atmel.com/dyn/products/tools_card.asp?tool_id=2725), [AVR Studio 5](http://www.atmel.com/dyn/products/tools_card.asp?tool_id=17212) or later
  * [LUFA library](http://code.google.com/p/lufa-lib/)

Note, that although LUFA is relying on [WinAVR](http://sourceforge.net/projects/winavr/) for the GNU Tools (C compiler and such), the makefile for the SDR MK1 is able to use the toolchain provided with AVR Studio 5. If you are using the AVR Studio 4, you either have to download a separate [AVR Toolchain Installer](http://www.atmel.com/dyn/products/tools_card.asp?tool_id=2725) or install WinAVR. (I really haven't tested it with AVR Studio 4 + AVR Toolchain combo, so WinAVR approach is recommended for AVR Studio 4.)


---


![http://sdr-mk1.googlecode.com/svn/wiki/88x31.png](http://sdr-mk1.googlecode.com/svn/wiki/88x31.png)

The work is licensed under the [Creative Commons](http://creativecommons.org/licenses/) [Attribution-NonCommercial-ShareAlike (CC BY-NC-SA)](http://creativecommons.org/licenses/by-nc-sa/3.0/) License. Basically, you are free to remix, tweak, and build upon this work non-commercially, as long as you credit the original work properly and license your new creations under the identical terms. You have to, however, ask for permission if you are planning to use the material or inherited works commercially.
