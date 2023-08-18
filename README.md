# EFI-GIGABYTE-A320M-S2H-V2-RYZEN-4650G-RX5500XT
EFI for Hackintosh with a Gigabyte A320M S2H V2, Ryzen 5 Pro 4650G and a Jieshuo RX 5500 XT

**Latest working macOS**: Ventura
<br>
**Current OpenCore**: 0.9.4
<br>
**SMBIOS Used**: MacPro 7,1 (works with an iMacPro1,1 too, you need to generate your own SMBIOS and Serial)

## Complete hardware specs
- AMD Ryzen 5 Pro 4650G 6-core (all of them working)
- Gigabyte A320 S2H V2 @ F53
- Jieshuo RX 5500 XT
- 2x 8Gb DDR4 3200Mhz Juhor with XMP Enabled
- Realtek RTL8111 Gigabit Ethernet
- Reltek ALC887 Audio
- Wifi/BT replaced by Fenvi BCM9436 - Work OOB

## What works
- macOS Big Sur, macOS Catalina and macOS Monterey
- Audio
- HDMI/DP (in dGPU - Works OOB)
- All USB ports
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Temperature monitoring for everything except GPU
- Shutdown/Reboot/Update to newer macOS builds over time

## What doesn't work
- Microphone JACK (Needs an USB Mic)
- Sleep? Never got the chance to test it, my hackintosh is up 24/7

## Kexts used:
- AMDRyzenCPUPowerManagement.kext
- AppleALC.kext
- AppleMCEReporterDisabler.kext
- Lilu.kext
- NVMeFix.kext
- RealtekRTL8111.kext
- RestrictEvents.kext
- SATA-unsupported.kext
- SMCAMDProcessor.kext
- USBMap.kext
- VirtualSMC.kext
- WhateverGreen.kext
