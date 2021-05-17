## Recovery Device Tree for the Samsung Galaxy S21+ 5G (Exynos)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_t2s-eng
make recoveryimage
```

Kernel source:
https://github.com/mohammad92/android_kernel_samsung_exynos2100
