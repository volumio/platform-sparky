# platform-sparky
Platform files for Allo SparkySBC

Kernel Sources: https://github.com/sparkysbc/Linux

This repo contains all files, used by the Volumio Builder to create a **sparky** image

- Allo Piano 2.0 & Piano 2.1 DAC firmware INCLUDING Texas Instruments license
- kernel files (kernel, modules, firmware)
- u-boot (image, dtb, uenv.txt)
- other files. e.g. kernel configuration, initial patches for overlayfs backport etc.


**Files for sparky, kernel version 3.10.37**
- 20160922: Initial, full Volumio 2 support on kernel 3.10.37 with backported overlayfs
- 20161013: Added more wifi drivers
- 20161013: Added missing Atheros ath09-htc
            removed IP tunneling
- 20161013: Compiled from the Allo kernel github
            added WiFi module RTL8192E
- 20161110: Compiled from the Allo kernel github
	    (Allo's spdif module addition)
- 20161128: Patched the Makefile for the usb host drivers and enabled USB 3.0 (XHCI)
- 20161130: Allo enabled emmc, allowing images working both for sd and emmc	    
- 20161201: Allo's latest kernel repo with patched makefile for usb host drivers
- 20161202: Updated bootlogo and DSP firmware
- 20161207: Re-compiled for RTL8188 WiFi
- 20161208: Bumped kernel version 3.10.37 -> 3.10.38
	    Piano/ Pinano+ DAC updated 
- 20161213: (Allo) Corrected config
- 20170102: (Allo) Subwoofer issue fixed, thermal sensor message removed  
- 20170116: Pulled latest Allo changes and re-compiled  
- 20170126: Pulled and recomipled the kernel: adds sparky's initial heartbeat
- 20170202: (Allo) Fixed shairport issue  
            Raised bootdelay (on cmdline) to 20s
- 20170214: Reduced usb 2.0 boot time/ removed bootdelay from uEnv.txt
- 20170217: Removed touchscreens, which slipped in while pullng kernel on 02.02.2017
- 20170401: Added snd_aloop to support brutefir  
- 20170618: (Allo) USB Bridge Support, remote addition, uart5 enable, spi enable, Dual Mono  
- 20170630: (Allo) Piano 2.1 driver update: added Dual Mode as a separate mixer mode
- 20170706: (Allo) Piano 2.1 driver fix  
- 20170809: Added adapted hotspot.sh script for Sparky  
- 20170925: (Allo) Added USB-2.0 patches, DSD native enable for Sparky
- 20171004: (Allo) Bug fix: Piano2.1: mode init & max volume. Hiface driver added for usb dacs

