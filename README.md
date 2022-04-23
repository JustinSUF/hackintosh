# AMD Ryzen Hackintosh

[![MacOS version](https://img.shields.io/badge/Catalina-10.15.7-informational.svg)](https://www.apple.com/macos) [![MacOS version](https://img.shields.io/badge/Bigsur-11.6.5-informational.svg)](https://www.apple.com/macos) [![MacOS version](https://img.shields.io/badge/Monterey-12.4%20beta2-informational.svg)](https://www.apple.com/macos)\
[![OpenCore version](https://img.shields.io/badge/OpenCore-0.8.0-informational.svg)](https://github.com/acidanthera/OpenCorePkg)\
[![GitHub](https://img.shields.io/github/license/sileshn/Ryzentosh?style=flat-square)](https://github.com/sileshn/Ryzentosh/blob/master/LICENSE)

## Important information
According to sileshn, This EFI supports only MacOS versions catalina(10.15) and higher. so it doesn't work on Mojave and High Sierra.

<a href='https://postimg.cc/RJLKgSYB' target='_blank'><img src='https://i.postimg.cc/RJLKgSYB/Screenshot-2021-07-23-at-7-24-32-AM.png' border='0' alt='Screenshot-2021-07-23-at-7-24-32-AM'/></a> <a href='http://postimg.cc/PCfByjhR' target='_blank'><img src='https://i.postimg.cc/PCfByjhR/Screenshot-2022-03-15-at-9.png' border='0' alt='Screenshot-2022-03-15-at-9'/></a> <a href='http://postimg.cc/JyLGWKYF' target='_blank'><img src='https://i.postimg.cc/JyLGWKYF/Screen-Shot-2022-04-20-at-2.png' border='0' alt='Screen-Shot-2022-04-20-at-2'/></a>

## Disclaimer
Use at your own risk. I take no responsiblity if your turns into a fireball or ends up hacking the government. Create unique SMBios values for your computer. Don't steal mine. Thanks.

## Specification

| Component        | Model                                              |
| ---------------- | ---------------------------------------------------|
| CPU              | AMD Ryzen 5 2600x                                  |
| MotherBoard      | Gigabyte B450 Aorus Pro Wifi                       |
| Wifi/Bluetooth   | Intel(R) Dual Band Wireless-AC 3168                |
| OS Disk          | HGST 1TB 5400RPM Laptop drive, yeah i know its awful but its all i got rn. ok?
| RAM              | 4x 8GB TForce smth which comes out to be 32gb      |
| GPU              | XFX AMD Radeon RX 580 8 GB                         |

## Working (according to sileshn)

* iCloud
* Bluetooth
* Ethernet
* Wifi
* iServices & drm

## Not Working (also according to sileshn)

* Sleep ( on Monterey )
* Sidecar

## Patches, Drivers & Kexts

* [AirportBrcmFixup](https://github.com/acidanthera/AirportBrcmFixup)
* [AppleALC](https://github.com/acidanthera/AppleALC)
* [AppleMCEReporterDisabler](https://github.com/acidanthera/bugtracker/files/3703498/AppleMCEReporterDisabler.kext.zip)
* [BrcmPatchRAM](https://github.com/acidanthera/BrcmPatchRAM)
* [Kernel Patches](https://github.com/AMD-OSX/AMD_Vanilla) ( Newer universal patches introduced in [this](https://github.com/sileshn/Ryzentosh/commit/adcb87fa003a0e77afaded014984a00ecb07b775) commit requires you to update the core count of your processor. For more information on this subject, click [here](https://github.com/AMD-OSX/AMD_Vanilla#read-me-first).)
* [Lilu](https://github.com/acidanthera/Lilu)
* [OpenCore](https://github.com/acidanthera/OpenCorePkg)
* [RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X)
* [RestrictEvents](https://github.com/acidanthera/RestrictEvents)
* [VirtualSMC](https://github.com/acidanthera/VirtualSMC)
* [WhateverGreen](https://github.com/acidanthera/WhateverGreen)

## Bootloader

I have Monterey and Windows 10 Dual Booted.

[![10022018.png](https://i.postimg.cc/TwDYkvGy/10022018.png)](https://postimg.cc/cgdSHjvZ)

## Credits and links

* [OpenCore install guide](https://dortania.github.io/OpenCore-Install-Guide)
* [Hackintool](https://www.hackintosh-forum.de/forum/thread/38316-hackintool-ehemals-intel-fb-patcher)
* [OpenCore-Legacy-Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher)
* [OpenCore-Legacy-Patcher guide](https://dortania.github.io/OpenCore-Legacy-Patcher)
* [Original Github](https://github.com/sileshn/Ryzentosh)
