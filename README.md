This is a device tree for BLu Studio X8 HD (MT6592) which is based on MT6592 SoC.
Based on Stock Kitkat kernel (3.4.67)


# Specifications:-
   * CPU	1.4GHz Octa-Core MT6592
   * Memory	512MB RAM
   * Android Version 4.4.2 & 5.1.1
   * Storage	16GB
   * Battery	2500 mAh
   * Display	5.0" 720 x 1280 DPI 320
   * Rear Camera	8MP
   * Front Camera	3MP


# Working
  * Dual SIM
  * Wifi
  * VPN
  * Bluetooth
  * Audio
  * Sensors
  * Camera (photo and video recording)
  * GPS
  * Screen Record
  * HD games
  * Tethering (Wifi, Bluetooth and USB)



# Build

  * repo init -u git://github.com/LineageOS/android.git -b cm-13.0
  * repo sync
  * git clone https://github.com/LOS14MTK/android_device_blu_studio_x8_hd.git -b cm-14.0 device/blu/studio_x8_hd
  * git clone https://github.com/LOS14MTK/proprietary_vendor_blu.git -b cm-14.0 vendor/blu
  * cd device/blu/studio_x8_hd/patches
  * source apply.sh 
  * source build/envsetup.sh
  * brunch studio_x8_hd
  * Done :)
  
  # Credits/Thanks to:-
  * Fire855 
  * Axet
  * chrmhoffmann
  * DerTeufel1980
  * Al3XKOoL
  * xen0n
  * kashifmin
  * Santhosh M
  * ariafan
  * hyperion70
  * tribetmen
  * CyanogenMod Team
  * Tirth Patel
  * Kishan Patel
  * Yazad Madan 
  * & Me :)
