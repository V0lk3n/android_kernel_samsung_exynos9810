# Nethunter Kernel - Samsung Galaxy S9 (Exynos9810)

This is a Nethunter Kernel Port of LineageOS 20 (Android 13) for Samsung Galaxy S9 Exynos9810 (starlte).

## Feature

- BT_RFCOMM
- Internal_BT
- Injection
- ATH9K_HTC
- RTL88XXAU
- NFS
- CAN (Full support as modules)

## Build

Builded using Kali Nethunter Kernel Builder.

local.config files can be found in the /nh_files folder.

You can create the Nethunter Zip file with the Kali-Nethunter-Installer using the command bellow :

Full Chroot :
./build.py -k starlte-los -fs full

Kernel Only :
./build.py -k starlte-los -i

For more alternative, feel free to read the Kali-Nethunter-Installer documentation
## Flash

Can be flashed using TWRP or Magisk.

I recommand to flash the nethunter zip and flash the kernel again after that.

## Issue

Any issue? Let me know!
