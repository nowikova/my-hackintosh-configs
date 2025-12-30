### Hackintosh, codename "Ikari": Gigabyte H510, Intel 11th-gen proccessor, Radeon RX 5600 XT, 16 GB RAM

## [Reddit post](https://www.reddit.com/r/hackintosh/comments/17rpjy0/macos_11_big_sur_11th_gen_intel_rx_5600xt/) | [Source](https://github.com/neppedboy/h510-11thgen-hackintosh/tree/main/source/EFI) | [Opencore Guide](https://dortania.github.io/OpenCore-Install-Guide/)

![About Me s2ection on functional macOS](https://nowa.dokuritsu.cc/personal/hacks/intel/nov2023/h510-11th-gen-intel/desktop.png)

This is my personal EFI for my home PC. You can use it for your PC if your hardware is [simillar](https://github.com/nowikova/my-hackintosh-configs/tree/h510-11th-gen-intel?tab=readme-ov-file#computer-specs)

# DONT USE THIS AS IT IS
It WONT work normally. You should make some changes before using this EFI configuration
* Configure SMBIOS
* Enable Verbose and debug things on boot-args
* Luck :P

## Computer specs
* Motherboard: Gigabyte H510s2
* CPU: Intel Core i5-11400F (12 threads, 6 core)
* RAM: AMD Radeon R9 Gamer Series (R948G3206U2SU) 8Gb x 2
* GPU: AMD Radeon RX 5600 XT (MSI OC Mech edition)
* SSD (NVMe): Kingston NV1 512Gb

## Misc
* Audio Card: Realtek ALC897
* Bluetooth module: ASUS BT400 (Bluetooth 4)
* Bootloader: OpenCore (v0.9.5)

## What is supported
* GPU Acceleration with Metal apps
* Bluetooth pairing with any device (also with airpods)
* Virtualization
* Other functions of macOS (ex TIme Machine backuping)

## Tested macOS 
* macOS Big Sur
* macOS Monterey
* macOS Ventura (up to 13.4)
* macOS Sonoma (Dev Beta 1, Release 14.0)

## Features
* [Mapped RAM](https://dortania.github.io/OpenCore-Post-Install/universal/memory.html#mapping-our-memory)
* [Configured bootloader interface](https://dortania.github.io/OpenCore-Post-Install/cosmetic/gui.html#setting-up-opencore-s-gui)
* [Changed SMBIOS for macOS only](https://www.reddit.com/r/hackintosh/comments/lnh66w/windows_through_opencore_shows_as_macpro/)

## Another useful screenshots

### Neofetch Information
![Neofetch Info](https://nowa.dokuritsu.cc/personal/hacks/intel/nov2023/h510-11th-gen-intel/neofetch.png)

### Hackintool Information 
![Hackintool](https://nowa.dokuritsu.cc/personal/hacks/intel/nov2023/h510-11th-gen-intel/hackintool.png)
