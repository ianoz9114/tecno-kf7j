**guide for rooting tecno spark 7 pro (kf7j)**


**Prerequisites**

- Computer with adb and fastboot installed (they're in the Android Platform Tools)
- The phone with an unlocked bootloader
- A backup of any important things you might have on the phone
- If you don't have the bootloader unlocked type "fastboot flashing unlock" and follow the instructions

**[Steps]**

-     Download files provided here 
-     save to your pc(or linux)
-     open terminal 
-     enable usb debugging 
-     unlock bootloader
-     type adb devices then follow instrcutions on android screen
-     Put your device in fastboot ( run adb reboot bootloader) 
-     type fastboot devices to check if the device is detected
-     type fastboot flashing unlock then follow the instructions on screen 
-     fastboot flash boot magisk_patched-25200_xLsNc.img Done!
-     fastboot flash vbmeta vbmeta.img  Done!

    Done
**CAUTION** 
i patched the boot image using magisk version 25.2
the images here were tested on build with v373, kf7j  if you do not know what this means, please contact first 


**CONTACT**

[contact](https://chat.whatsapp.com/IZGmkyP2afz4fRDg6EYfOi)
