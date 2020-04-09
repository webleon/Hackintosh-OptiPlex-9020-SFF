# Hackintosh-OptiPlex-9020-SFF
**Only tested on Clover EFI bootloader.**

**2020-04-09**
* Update MacOS to Catalina 10.15.4
* Tested on budget Wi-Fi/BT Card BCM943224PCIEBT2

This is the Hackintosh EFI Folder for Dell OptiPlex 9020 Small Form Factor. The configuration settings support MacOS Catalina 10.15.3 with resolution up to 2560 x 1440. HiPDI support can be actived with [One Key HiDPI](https://github.com/xzhih/one-key-hidpi/blob/master/README.md) script. Because wake up from deep sleep will cause a kernel panic, so I blocked sleep in BIOS. You will have to **generate a new serial and SmUUID** before login to your iCloud account.

## Hardware Specs
* **Barebone Chassis**: [Dell OptiPlex 9020 Small Form Factor](https://www.dell.com/support/manuals/lv/en/lvbsdt1/optiplex-9020-desktop/opt9020sffom-v2/) with 2 DP Ports
* **CPU**: [Intel® Core™ i7-4790](https://ark.intel.com/products/80806/intel-core-i7-4790-processor-8m-cache-up-to-4-00-ghz.html)
* **iGPU**: Intel® HD Graphics 4600
* **RAM**: 32GB DDR3 1600 Daul Channel 
* **HDD**: Seagate BarraCuda SSD 500GB
* **Wi-Fi & Bluetooth**: BCM943224PCIEBT2 with PCIe Adapter

## What Works
* CPU Turbo Boost & Thermal Throttling
* Integrated Graphics with acceleration
* Daul monitor output at 2560 x 1440
* Integrated Audio Output
* All USB Ports
* LAN & Wireless Network
* Airdrop & Airplay
* Sleep & Wakeup

## BIOS Settings
- General → Advanced Boot Options: ***uncheck***
- System Configuration → SATA Operation: ***AHCI***
- Secure Boot → Secure Boot Enable: ***Disabled***
- Power Management → Block Sleep: ***check***
- Virtualization Support → VT for Direct I/O: ***uncheck***
