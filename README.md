G900F Omega Kernel KK 4.4.2

Based on Samsung kernel sources Kit Kat

****************************************************

1. How to Build

- get Toolchain
SaberMod Toolchain 4.9.0
https://bitbucket.org/Cl3Kener/sm-arm-eabi-4.9/overview

- Build
		$ sudo su
		$ export ARCH=arm
		$ export CROSS_COMPILE=/home/user/Toolchain_dir/sm-arm-eabi-4.9/bin/arm-eabi-
		$ make msm8974_sec_defconfig VARIANT_DEFCONFIG=msm8974pro_sec_klte_eur_defconfig SELINUX_DEFCONFIG=selinux_defconfig
		$ make
		
2. Output filesS
		- Kernel : output/arch/arm/boot/zImage

3. How to Clean	
		$ make clean

****************************************************
