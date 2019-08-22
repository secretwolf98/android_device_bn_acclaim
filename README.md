# android_device_bn_acclaim

Make the directory: mkdir lin13

CD to the directory: cd lin13

Repo: repo init -u git://github.com/LineageOS/android.git -b cm-13.0

Repo sync: repo sync -j4

Device repo: repo init -u git://github.com/secretwolf98/android_device_bn_acclaim.git -b cm-13.0 device/bn/acclaim

Device kernel repo: repo init -u git://github.com/LineageOS/android_kernel_bn_acclaim.git -b cm-13.0 kernel/bn/acclaim

Breakfast the device: breakfast acclaim

Make the device: make -j4 bacon

Make the device otapackage: make -j4 otapackage


If the build is successful, go and flash the ROM in TWRP.
