esp32-wrover-kit PlatformIO for Apple M1 + JTAG debugging
=====================================

macOS Ventura 13.3.1 (22E261) here

could not get the serial console to work (just NULL chars received)

fixed by installing the beta 1.5.0 FTDI driver from https://ftdichip.com/drivers/vcp-drivers/

https://ftdichip.com/wp-content/uploads/2022/06/FTDIUSBSerialDextInstaller_1_5_0.dmg

this example project now works on the M1, both serial console and JTAG debugging

