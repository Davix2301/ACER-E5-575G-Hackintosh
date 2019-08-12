# ACER-E5-575G-Hackintosh
Files I used to successfully hackintosh my laptop


SPECS:

i5-7200u
8gb 2400mhz
Nvidia 940mx 2gb DDR5
Intel HD620
500gb SATA 3 HDD 
Qualcomm Atheros QCA9377 wifi card
Realtek RTL811/8168/8411 gigabit ethernet
Realtek ALC255 sound card


Things that work:
Ethernet
Touchpad, almost all gestures work (set to BASIC, didn't test with advanced yet)
iGPU
Audio (fn keys to lower/raise volume work too)
Battery percentage
Activity and charge leds
All 3.0 and 2.0 USB ports
3.1 type c works with a C to 2.O A adapter just fine
Sleep,resume,reboot and shutdown

Things that don't and never will work:
940mx (No web drivers in Mojave, could work in High Sierra)
Wifi card (No kext for it)

Things that maybe will work:
Dvd drive (was recognized the first times but now doesnt anymore)
SD card reader (maybe there's some kext for it, I don't really use it so, in case you can find its name with DCPI manager)
Brightness (need some time to figure it out, feel free to suggest me how if you manage to do it)

Not tested:
SSD/HDD in a caddy in place of the dvd drive (will do in a couple months)
VGA (should work)
HDMI (should not work)


ADVICES:
USE VANILLA INSTALL
If install usb doesn't get recognized just switch usb port and reboot until the pc does
If it reboots after apple logo just after you pressed install from the install usb, just put the ram in the other slot


