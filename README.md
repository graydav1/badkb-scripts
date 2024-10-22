# badkb-scripts
This repo contains a few BadKB scripts to be used with the Flipper Zero.

## WIN11-OOBE-GET-AUTOPILOT-HASH
This script is to be run at the Windows 11 OOBE screen (i.e. right after you've installed a fresh copy of Windows 11) and will get the hardware hash to be used with Windows Autopilot. You'll need to change the `-GroupTag` flag (or set it manually after the fact) and you'll also need to change the drive letter from `D:` if the computer has a DVD drive or something else that would mean `D:` is not the USB stick used to install Windows. 

## WIN11-INSTALL.txt
This script automates the installation of Windows 11 using a previously created Media Creation Tool USB stick. It may require tweaking to run correctly, as menu options may change, and timings may vary depending on your hardware. This is useful if you need to install or reinstall Windows 11 on a bunch of machines

## WIFI-JOIN.txt
This script joins a Windows machine to wifi using the command line. You'll need to change the SSID and password to suit your environment, and you need to make sure the hex string (which is the SSID in hex) is changed too
