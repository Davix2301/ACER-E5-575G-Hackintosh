# ACER-E5-575G-Hackintosh
Mojave release = Clover
Ventura release = OpenCore

Strongly advised to use OpenCore and Ventura.
ONLY USE ON VANILLA INSTALLS.


SPECS:

i5-7200u   
8gb 2400mhz single channel 
Nvidia 940mx 2gb DDR5 
Intel HD620 
120GB Sata SSD + 500GB SATA HDD in a DVD to HDD caddy adapter   
Qualcomm Atheros QCA9377 wifi card 
Realtek RTL811/8168/8411 gigabit ethernet
Realtek ALC255 sound card (Works with the first id from AppleAlc github)


Things that work: 
Ethernet  
Touchpad, almost all gestures work (set to BASIC with VoodooPS2, works in ADVANCED with VoodooIC2 and VoodooSynaptics)  
iGPU 
Audio (fn keys to lower/raise volume work too)  
Battery percentage  
Activity and charge leds  
All 3.0 and 2.0 USB ports 
3.1 type c works with a C to 2.O A adapter just fine  
Sleep,resume,reboot and shutdown  
VGA Port (it's hardwired to the Intel HD620)

Things that don't and never will work:   
940mx (could work in High Sierra, didn't test, GPU is currently disabled in Ventura) 
Wifi card (No kext for it)  
HDMI port (it's hardwired to the NVidia GPU)

Things that maybe will work:  
Dvd drive (mine was broken) 
SD card reader (maybe there's some kext for it, I don't really use it)  
Brightness keys (works fine from the settings, in both Mojave and Ventura)  

 

 
USE VANILLA INSTALL 
If install usb doesn't get recognized just switch usb port and reboot until the pc does 
If it reboots after apple logo just after you pressed install from the install usb, just put the ram in the other slot  


