![NetHunter_banner](https://github.com/user-attachments/assets/715a09a6-2b10-4553-80f9-4aee1c4a0ad2)

# NetHunter Kernel - Samsung Galaxy S9 Exynos9810 Starlte

Official lineage documentation has been moved to <a href="Documentation/README">Documentation</a>

This is a Kernel port for Kali NetHunter from LineageOS 20

Made for Samsung Galaxy S9 (Exynos9810/Starlte)

## Building

You can find official build on Kali Linux website, or build it yourself from my sources.

First, clone this repository with it's submodules.

```
git clone --recurse-submodules https://github.com/V0lk3n/nethunter_kernel_samsung_exynos9810.git -b nethunter-lineage-20
```

Enter into Kali Linux Kernel Builder and copy local.config to it.

```
cd nethunter_kernel_samsung_exynos9810/kali-nethunter-kernel-builder
cp ../nh_files/local.config .
```
Build the kernel.

```
./build.sh
```

For more informations, take a read of the official Kali Linux Nethunter documentations.
