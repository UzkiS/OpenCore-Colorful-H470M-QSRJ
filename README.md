# OpenCore for Colorful H470M with QSRJ and HD630

OpenCore for Colorful H470M

## OC information

- OC Version: 0.7.9
- Tested OS Version: 12.3 (21E230)
- Tested resolution: 1920\*1080

## Working

- WIFI(Broadcom)
- Sound
- USB Port(When the front usb is invalid, you may need to [remap your usb](https://github.com/USBToolBox/tool))
- Sleep

## Before installation

### star this project ( > ω < )

### Edit config.plist

**At first, please complete the 'PlatformInfo' by yourself.** [https://dortania.github.io/OpenCore-Install-Guide/config.plist/comet-lake.html#platforminfo](https://dortania.github.io/OpenCore-Install-Guide/config.plist/comet-lake.html#platforminfo)

- PlatformInfo>Generic>MLB
- PlatformInfo>Generic>ROM
- PlatformInfo>Generic>SystemSerialNumber
- PlatformInfo>Generic>SystemUUID

### BIOS Settings

#### Disable

- Secure Boot
- Serial/COM Port
- TPM

#### Set

- Storage -> Storage Options -> SATA Emulation > AHCI

## Kext information

| Name                                                                | Version |                                                                                                           |
| ------------------------------------------------------------------- | ------- | --------------------------------------------------------------------------------------------------------- |
| [Lilu](https://github.com/acidanthera/Lilu)                         | 1.6.0   | ![GitHub release (latest by date)](https://img.shields.io/github/v/release/acidanthera/Lilu)              |
| [VirtualSMC](https://github.com/acidanthera/VirtualSMC)             | 1.2.9   | ![GitHub release (latest by date)](https://img.shields.io/github/v/release/acidanthera/VirtualSMC)        |
| [WhateverGreen](https://github.com/acidanthera/WhateverGreen)       | 1.5.8   | ![GitHub release (latest by date)](https://img.shields.io/github/v/release/acidanthera/WhateverGreen)     |
| [AppleALC](https://github.com/acidanthera/AppleALC)                 | 1.7.0   | ![GitHub release (latest by date)](https://img.shields.io/github/v/release/acidanthera/AppleALC)          |
| [AirportBrcmFixup](https://github.com/acidanthera/AirportBrcmFixup) | 2.1.4   | ![GitHub release (latest by date)](https://img.shields.io/github/v/release/acidanthera/AirportBrcmFixup)  |
| [BrcmPatchRAM](https://github.com/acidanthera/BrcmPatchRAM)         | 2.6.1   | ![GitHub release (latest by date)](https://img.shields.io/github/v/release/acidanthera/BrcmPatchRAM)      |
| [RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X)  | 2.4.2   | ![GitHub release (latest by date)](https://img.shields.io/github/v/release/Mieze/RTL8111_driver_for_OS_X) |
| [HibernationFixup](https://github.com/acidanthera/HibernationFixup) | 1.4.5   | ![GitHub release (latest by date)](https://img.shields.io/github/v/release/acidanthera/HibernationFixup)  |
| [NVMeFix](https://github.com/acidanthera/NVMeFix)                   | 1.0.9   | ![GitHub release (latest by date)](https://img.shields.io/github/v/release/acidanthera/NVMeFix)           |
| [USBToolBox](https://github.com/USBToolBox/kext)                    | 1.1.1   | ![GitHub release (latest by date)](https://img.shields.io/github/v/release/USBToolBox/kext)               |
