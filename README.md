# Legion_Y530_Hackintosh

My setup:
- Lenovo legion Y530-15ICH (81FV)
- 16Gb ram
- i5-8300H @ 2.3GHz
- Intel 450Gb SATA SSD
- Samsung EVO 960 256Gb M.2 (disabled in MacOS with SSDT-DNVMe.aml)
- Original Realtek Wi-fi M.2 card replaced with BCM94352Z


The current efi version works with Sonoma 14.2

The config is based on (huge thanks to the author)
https://github.com/chilledHamza/Hackintosh_Legion_Y530


When setting this up, follow the guide for the serial number setup from this repo: https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh


To enable wifi on legacy wifi cards (such as BCM4352 in my config) folow this guide from step 8 
https://elitemacx86.com/threads/how-to-fix-broadcom-wifi-on-macos-sonoma-and-later.1415/
- reset NVRAM
- boot into system
- run OpenCore Legacy Patcher https://dortania.github.io/OpenCore-Legacy-Patcher/
- click on Post Install Root Patch
- once suggested - reboot
- reset NVRAM again
- boot into system - wifi should be working



While setting up this config the following setups were used as reference, huge thanks to those:
- https://github.com/xiaoMGitHub/LEGION_Y7000Series_Hackintosh
- https://github.com/yusufklncc/Lenovo-Legion-5-Hackintosh
