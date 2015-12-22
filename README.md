#Device tree for the OnePlus 2

###Syncing repo
Add this to your localmanifest
```xml
<manifest>
  <project path="device/oneplus/oneplus2" name="oneplus2-dev/android_device_oneplus_oneplus2" remote="github" revision="cm-13.0" />
  <project path="kernel/oneplus/msm8994" name="oneplus2-dev/android_kernel_oneplus_msm8994" remote="github" revision="cm-13.0" />
  <project path="vendor/oneplus" name="oneplus2-dev/android_vendor_oneplus" remote="github" revision="cm-13.0" />
  <project path="external/sony/boringssl-compat" name="oneplus2-dev/android_external_sony_boringssl-compat" remote="github" revision="cm-13.0" />
  </manifest>
```

###Building
```bash
. build/envsetup.sh
lunch cm_oneplus2-(eng/userdebug/user)
make #recipe
```
OR
```bash
. build/envsetup.sh
brunch oneplus2
```

Copyright 2015 - The CyanogenMod Project

Device configuration for OnePlus Two.
=====================================

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Quad-core 1.8 GHz ARM® Cortex™ A57 and quad-core 1.5 GHz ARM® Cortex™ A53
CHIPSET | Qualcomm MSM8994 Snapdragon 810
GPU     | Adreno 430
Memory  | 3/4 GB
Shipped Android Version | 5.1.1
Storage | 16/64 GB
Battery | 3300 mAh (non-removable)
Dimensions | 151.8 x 74.9 x 9.85 mm
Display | 1.920 x 1.080
Rear Camera  | 13 MP, dual-LED flash
Front Camera | 5 MP
Release Date | July 2015

![OnePlus Two](http://cdn2.gsmarena.com/vv/pics/oneplus/oneplus-two-1.jpg "OnePlus Two")


Credits :-
@Grarak
@regalstreak
@manups4e
@Martinusbe
@root-expert
@DavidVazGuijarro
@elgithubo
