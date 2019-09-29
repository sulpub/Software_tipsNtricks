# Software_tipsNtricks
Tips and tricks software.

# Thunderbird mailer
## Deleted profile accidentally

```
Under Windows run the command line
thunderbird.exe -p //for open le list of Thunderbird profile
```

# Install TWRP and Root Xiaomi Pocophone F1

Before you begin, it is important to have all the tools at hand. you will need:

*Recharge your smartphone battery more than 70%
*Install Xiaomi USB drivers, tutorial: Download And Install Xiaomi Pocophone F1 USB Driver
*SDK drivers, tutorial: How to install ADB, Fastboot, and Google USB driver in 15 seconds!!
*Unlock Bootloader of Xiaomi, tutorial: Unlock bootloader of Xiaomi smartphone
*Download the Magisk-v16.0.zip file: Magisk-v16.6.zip
*Download TWRP Recovery for Xiaomi Pocophone F1 & Rename the file to recovery.img: Download link
*Download Force encryption disabler: Download link


## ENABLE USB DEBUGGING 

1. Go to Settings> About phone
2. Find the MIUI Version and press 8 times on it:
3. Return to the previous screen. Go to Additional Settings

You will see that a line has appeared: “Developers Options”

4. Press and check “USB Debugging” &  “OEM unlocking”

## Install TWRP Recovery on your Xiaomi Pocophone F1

1- Open the folder where ADB and Fastboot are located on your computer and Copy the recovery.img file on the ADB folder

2- In an empty area, hold down the shift key and right-click with the mouse, the context menu will contain an entry Open command window here

3- To Restart your Xiaomi Pocophone F1 in Fastboot mode:

    adb reboot bootloader

4- To Verify that the phone is recognized in Fastboot mode Type this command:

    fastboot flash recovery recovery.img
    fastboot boot recovery.img            //for boot in TWRP

5- You have successfully Flashed TWRP in your Xiaomi Pocophone F1.

## Root Xiaomi Pocophone F1

1. Copy the Magisk.zip & Force encryption disabler.zip files on your internal storage or SD card
2. Restart your Xiaomi Pocophone F1 in Fastboot mode:

    press & hold  the “Volume Down + Power button” at the same time for about 5 seconds

3. Install and flash Force encryption disabler:

    Choose “Install” then choose “Force encryption disabler“
    Press the return key
    Just press “Reboot” to restart the phone in recovery mode again

4. Install and flash Magisk:

    Choose “Install” then choose “Magisk.zip“
    Press the return key
    Just press “Reboot” to restart the phone in normal mode.

5. Now Download & install the apk file “MagiskManager.apk”
6. Restart your device.

Now you have successfully rooted your Xiaomi Pocophone F1.

## Check Your Root of Xiaomi Pocophone F1

Download Root Checker app that allows you to check in seconds if your device is rooted or not.

Source : https://zfirmware.com/how-to-install-twrp-and-root-xiaomi-pocophone-f1/


# Virtualisation ubuntu under windows 10

1. Download you ISO file of UBUNTU OS.
2. Under windows 10 , Run this command "MMC" to open  Hyper-V virtualisation platform of windows 10.
3. In action zone, click new/virtual desktop.
4. Fill each stage on the wizard.
5. After all run the virtual machine and use UBUNTU under windows.
