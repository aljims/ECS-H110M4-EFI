# ECS H110M4-C43 OpenCore Configuration

![System Information](Docs/Info.png)

## System Information 

|  Part           |                                              |
|-----------------|----------------------------------------------|
|  Motherboard    |  ECS H110M4-C43, BIOS 2017/12/12             |
|  Chipset        |  H110                                        |
|  CPU            |  Intel Core i3-7100                          |
|  GPU            |  Intel HD Graphics 630                       |
|  Ethernet       |  Realtek 8111GN Gigabit Ethernet Controller  |
|  Wi-Fi          |  Realtek RTL8821CU (TP-Link T2UB Nano)       |
|  Bluetooth      |  Realtek RTL8821CU (TP-Link T2UB Nano)       |
|  Audio          |  Realtek ALC662                              |

## Tested macOS Version

|  macOS Version       |                      |
|----------------------|----------------------|
|  macos 15 Sequoia    |  ✅ Working          |
|  macos 13 Ventura    |  ✅ Working          |

## What's working:

* Graphics:            Yes
* Audio (line-out):    Yes
* Ethernet:            Yes
* Wi-Fi:               Yes
* USB Ports:           Yes

## Not working / Tested:

* Sleep: Disabled
* HDMI Audio
* Bluetooth: Not working

## Notes:

* Generate your own iMac18,1 SMBIOS. Use the Dortania Guide. This EFI contains prebuilt SSDT from https://dortania.github.io/Getting-Started-With-ACPI/ssdt-methods/ssdt-prebuilt.html. Using them boots my PC! :D

* This EFI includes boot chime and GUI bootloader. Verbose boot is disabled. Feel free to edit the plist.
