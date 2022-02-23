# hackintosh-asus-tuf-z490-plus

Hackintosh Monterey 12.2.1 build using OpenCore 0.7.8.

Drivers, SSDts and Kexts are at this time on the latest releases.

https://dortania.github.io/OpenCore-Install-Guide/

## Hardware Specifications
|||
|-|-|
|Motherboard|[ASUS TUF GAMING Z490 PLUS](https://www.asus.com/za/Motherboards-Components/Motherboards/TUF-Gaming/TUF-GAMING-Z490-PLUS/)|
|CPU|[Intel i3-10100F](https://www.intel.com/content/www/us/en/products/sku/203473/intel-core-i310100f-processor-6m-cache-up-to-4-30-ghz/specifications.html)|
|GPU|[AMD Radeon RX 570](https://www.amd.com/en/products/graphics/radeon-rx-570)|

### Motherboard - Asus Tuf Z490 Plus
|||
|-|-|
|Ethernet|Intel® I219-V|
|Audio|Realtek® ALC S1200A|
|BIOS|Version 2601|

### SSDTs

* [SSDT-AWAC.aml](https://github.com/dortania/Getting-Started-With-ACPI/blob/master/extra-files/compiled/SSDT-AWAC.aml)
* [SSDT-EC-USBX-DESKTOP.aml](https://github.com/dortania/Getting-Started-With-ACPI/blob/master/extra-files/compiled/SSDT-EC-USBX-DESKTOP.aml)
* [SSDT-PLUG-DRTNIA.aml](https://github.com/dortania/Getting-Started-With-ACPI/blob/master/extra-files/compiled/SSDT-PLUG-DRTNIA.aml)
* [SSDT-RHUB.aml](https://github.com/dortania/Getting-Started-With-ACPI/blob/master/extra-files/compiled/SSDT-RHUB.aml)

### Drivers

* [HfsPlus.efi](https://github.com/acidanthera/OcBinaryData/blob/master/Drivers/HfsPlus.efi)
* [OpenCanopy.efi](https://github.com/acidanthera/OpenCorePkg/tree/0.7.8)
* [OpenRuntime.efi](https://github.com/acidanthera/OpenCorePkg/tree/0.7.8)

### Kexts
* [AppleALC](https://github.com/acidanthera/AppleALC/releases/tag/1.6.9)
* [IntelMausi](https://github.com/acidanthera/IntelMausi)
* [Lilu](https://github.com/acidanthera/Lilu/releases/tag/1.6.0)
* [SMCProcessor](https://github.com/acidanthera/VirtualSMC/releases/tag/1.2.8)
* [SMCSuperIO](https://github.com/acidanthera/VirtualSMC/releases/tag/1.2.8)
* [USBMap] (https://github.com/corpnewt/USBMap))
* [VirtualSMC](https://github.com/acidanthera/VirtualSMC/releases/tag/1.2.8)
* [WhateverGreen](https://github.com/acidanthera/WhateverGreen/releases/tag/1.5.7)

### Theme
* [OpenCore Default](https://dortania.github.io/OpenCore-Post-Install/cosmetic/gui.html)
* [Blackosx LightGrey](https://github.com/blackosx/BsxDarkFenceLightGrey1)

[this OpenCore documentation](https://dortania.github.io/OpenCore-Install-Guide/config.plist/comet-lake.html) was used to build the config.plist

Ensure to do a OC Clean SnapShot from [ProperTree](https://github.com/corpnewt/ProperTree) to build up your config.plist once your EFI directory has been finalised.

## Known Issues

None this far.
