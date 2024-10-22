# badkb-scripts
This repo contains a few BadKB scripts to be used with the Flipper Zero.

## WIN11-OOBE-GET-AUTOPILOT-HASH
This script is to be run at the Windows 11 OOBE screen (i.e. right after you've installed a fresh copy of Windows 11) and will get the hardware hash to be used with Windows Autopilot. You'll need to change the `-GroupTag` flag (or set it manually after the fact) and you'll also need to change the drive letter from `D:` if the computer has a DVD drive or something else that would mean `D:` is not the USB stick used to install Windows. 
