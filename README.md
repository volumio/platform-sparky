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
 

