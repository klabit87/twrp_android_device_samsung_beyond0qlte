## Recovery Device Tree for the Samsung Galaxy S10e (Snapdragon)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch omni_beyond0qlte-eng
make recoveryimage
```

Kernel source:
https://github.com/mohammad92/android_kernel_samsung_sm8150
