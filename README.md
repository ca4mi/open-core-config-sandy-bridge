### Hardware
* Motherboard: Colorful C.H61U V27
* CPU: Quad Core [Intel Core i5](https://www.intel.com/content/www/us/en/products/sku/52206/intel-core-i52300-processor-6m-cache-up-to-3-10-ghz/specifications.html) | 2.79 GHz | Sandy Bridge
* GPU: ASUS GTX 770 DirectCU II OC 2 GB + kernel patch from [chirs1111](https://github.com/chris1111/Geforce-Kepler-patcher)
* Power Supply: COOLER MASTER|500 Watts| PFC Active MPW-5001-ACABN1
* SSD: Kingston 240 GB | [TRIM](https://en.wikipedia.org/wiki/Trim_(computing)) Enabled via Kernel 
* RAM: Envinda DDR3 1600 PCI-12800U-CL9 /only works 1333 MHz/
* Display: Asus PA279CV
* Keyboard & Mouse: Generic

### Bootloader and OS
* Bootloader: [OpenCore](https://github.com/acidanthera/OpenCorePkg)
* OS: MacOS Monterey **12.7.6**

Works on Monterey **12.7.6** above higher versions had issue with Nvidia GPU.
You can step-by-step guide though Open Core's [guide](https://dortania.github.io/OpenCore-Install-Guide/0).
conflig.plist's simbios based on **MacPro6,1**. Generate your own `MLB`, `SystemSerialNumber` using [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)

### Kernels
* [AppleALC.kext](https://github.com/acidanthera/AppleALC)
* [Lilu.kext](https://github.com/acidanthera/Lilu)
* [NVMeFix.kext](https://github.com/acidanthera/NVMeFix)
* RealtekRTL8100.kext
* [VirtualSMC.kext](https://github.com/acidanthera/VirtualSMC)
* [WhateverGreen.kext](https://github.com/acidanthera/WhateverGreen)

### Tools
* [MountEFI](https://github.com/corpnewt/MountEFI)
* [ProperTree](https://github.com/corpnewt/ProperTree)
* [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)

### Conclusion
Everything works expect sleeping.
