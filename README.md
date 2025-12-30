### Hackintosh, codename "Langley": AORus B550 Elite, AMD Ryzen 7 5700X, 32GB Ram. macOS 26 Beta 7

## [Source](https://github.com/nowikova/my-hackintosh-configs/tree/b550-5700x-amd/source/EFI) | [Opencore Guide](https://dortania.github.io/OpenCore-Install-Guide/)

![Screenshot from desktop](https://nowa.dokuritsu.cc/personal/hacks/amd/dec2025/b550-5700x-amd/desktop.png)

This is my personal EFI for my upgraded home PC. You can use it for your PC if your hardware is simillar or exact computer specs

# DONT USE THIS AS IT IS
It WONT work normally. You should make some changes before using this EFI configuration
* Configure SMBIOS
* Enable Verbose and debug things on boot-args
* Luck :P

## Computer specs
* Motherboard: GIGABYTE B550M AORUS ELITE
* CPU: AMD Ryzen 7 5700X 3.4GHz (8 Cores, 16 Threads)
* RAM: Kingston FURY Beast Black 32GB 2x16 3.2GHz [KF432C16BBK2/32]
* GPU: AMD Radeon RX 5600 XT (MSI OC Mech edition)
* SSD (SATA): Patriot Burst Elite [PBE240GS25SSDR]

## Misc
* Audio Card: Realtek ALC897
* Bluetooth module: ASUS BT400 (Bluetooth 4)
* Bootloader: OpenCore (v1.0.5)

## What is supported
* macOS Functions (ex Time Machine backuping)

## Not tested
* Virtualization (100% sure that i ain't work because of AMD CPU)
* Many of things (i tested only icon composer from Apple just for my unreleased project. i rarely use macos on my regular life)

## Tested macOS 
* macOS Seqouia (up to 15.6.1)
* macOS Tahoe (Beta 6)

## Features
* [Mapped RAM](https://dortania.github.io/OpenCore-Post-Install/universal/memory.html#mapping-our-memory)
* [Configured bootloader interface](https://dortania.github.io/OpenCore-Post-Install/cosmetic/gui.html#setting-up-opencore-s-gui)
* [Changed SMBIOS for macOS only](https://www.reddit.com/r/hackintosh/comments/lnh66w/windows_through_opencore_shows_as_macpro/)

