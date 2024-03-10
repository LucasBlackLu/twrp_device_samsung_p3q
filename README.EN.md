## Recovery Device Tree for the Samsung Galaxy S21 Ultra 5G (Snapdragon)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_p3q-eng
make recoveryimage
```

Kernel source:
https://github.com/LucasBlackLu/android_kernel_samsung_sm8350/tree/twrp-12.1
