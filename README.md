# badkb-scripts
This repo contains a few BadKB scripts to be used with the Flipper Zero.

## F12-BOOT-MENU.txt
This simple script just presses F12 1000 times, with half a second between each press (i.e. 50 seconds worth of presses). This is done solely to get into the boot menu on many systems, so you don't have to sit there mashing buttons while waiting for the machine to boot. You can run the script with the machine powered off, and when it turns on, it'll start

## LENOVO-SET-TIME.txt
This is to be used with the Lenovo Yoga X13 Gen 1, 2 and possibly 3. Due to the (rechargeable?) CMOS battery running flat in many of these machines, frequent resetting of the date and time is needed. This automates mst of that.

## WIFI-JOIN.txt
This script joins a Windows machine to wifi using the command line. You'll need to change the SSID and password to suit your environment, and you need to make sure the hex string (which is the SSID in hex) is changed too

## WIN11-INSTALL.txt
This script automates the installation of Windows 11 using a previously created Media Creation Tool USB stick. It may require tweaking to run correctly, as menu options may change, and timings may vary depending on your hardware. This is useful if you need to install or reinstall Windows 11 on a bunch of machines

## WIN11-OOBE-GET-AUTOPILOT-HASH.txt
This script is to be run at the Windows 11 OOBE screen (i.e. right after you've installed a fresh copy of Windows 11) and will get the hardware hash to be used with Windows Autopilot. You'll need to change the `-GroupTag` flag (or set it manually before uploading) and you'll also need to change the drive letter from `D:` if the computer has a DVD drive or something else that would mean `D:` is not the USB stick used to install Windows. 
