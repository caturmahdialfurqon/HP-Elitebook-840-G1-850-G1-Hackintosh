# Hackintosh HP Elitebook 850 G1

Previously, this hack has run Macos Catalina and Bigsur With `Clover Bootloader`.

## NEW UPDATES at Mon. 7 Oct 2024

## Update to MONTEREY Final With `OC 1.0.1 EFI R001`

This laptop has been in the warehouse for a long time,`since 2021` 😁, I tried updating from MacOS Bigsur to Monterey with `OpenCore`, because I (a bit) forgot how to use "Clover" 🤣 hehe, I think it's better to move from "Clover" to "OpenCore" because it's easier to set up, in my opinion.

## I have tested the following features for Monterey With `OC 1.0.1 EFI R001`

`Monterey 12.7.4` upgrade applied without any issues. This hack is working perfectly. <br>
With SMBIOS `MacBookPro11,4`

## About This Hack
<img src="/images/Screen Shot 2024-10-07 at 05.18.13.png" width=600>

## Bluetooth, WIFI And AIRDROP
- Both BlueTooth, WIFI Combo Works with AirportItlwm.kext v.2.3.0 <br>
  - (BlueTooth Modified as Third Party Dongle)
- Airdrop(Airport) Work
- Everything Works perfectly
  
<img src="/images/Screen Shot 2024-10-07 at 05.12.50.png" width=600>

## Perfomance

The performance of this Hackbook is still reliable

<img src="/images/Screen Shot 2024-10-07 at 05.22.30.png" width=600>

<br>

## OLD POST ABOUT Hackintosh With Catalina on 2024 

🤖 I don't think there's even much to post about hackintosh on HP elitbook 850 G1, either on google search or on github specific to hackintosh HP elitbook 850 G1, therefore I want to create a repository of my experience of hackintosh in HP elitebook 850 g1 for 2 years. from me wearing highsierra,mojave to catalina for now, will probably try BigSur if there is already a stable version. hopefully it can help. 🤖

This is a detailed macOS Catalina 10.15.6 Vanilla install guide for HP Elitebook 850 G1 , based on [RehabMan's HP guide](https://www.tonymacx86.com/threads/guide-hp-probook-elitebook-zbook-using-clover-uefi-hotpatch.261719/). [This guide](https://hackintosh.gitbook.io/-r-hackintosh-vanilla-desktop-guide/) is also really useful.

## SPEC

My HP Elitebook 850 G1 spec :
- **Processor**: Intel(R) Core(TM) i5-4300U CPU @ 1.90GHz (Haswell)
- **BIOS**: Version L71 Ver. 01.48
- **SSD**: ATA SK hynix SH920 2
- **RAM**: 8GB DDR3
- **DISPLAY**: 1920x1080 pixels (non-touch)
- **GPU**: Integrated, Intel HD Graphics 4400
- **AUDIO CODEC**: IDT92HD91BXX
- **ETHERNET**: Intel I218-LM
- **WIFIorBluetooth**: Intel Dual Band Wireless-N 7260AC 802.11 a/b/g/n (2 x2 ) WiFi  //  *It's not compatible, But its works with intwm.kext* 

Here you can check the different models: [HP Elitebook 850 G1](https://support.hp.com/id-en/document/c03963889/).

## BIOS Settings  
###### *Spam the F10 key*

Go to Advanced
   - Device configuration
      - Don't check Fn key switch (it has to be unchecked in order to the volume and brightness hotkeys work)
      - Change Video memory to 128MB
      - Disable wake on USB
      - Disable Virtualization Technology (VT-d)
      - Set SATA to AHCI
      - Built in device option
      - Disable Wake on LAN
      - UEFI with no CSM

## For Post Installation

- Here you can visit repository github from blint01 about post install hackintosh mojave on hp elitebook 840 g1 same as hp elitebook 850 g1 post install vanila Catalina
- **links** [blint01 github](https://github.com/blint01/hackintosh-mojave-HP-840-G1#creating-the-usb-installer/).




## I have tested the following features:

- UEFI booting via Clover
- built-in keyboard (with special function keys)
- built-in trackpad (basic gestures)
- HDMI video/audio with hotplug
- native USB3 with AppleUSBXHCI (USB2 works also)
- native audio with AppleHDA, including headphone
- built-in mic
- built-in camera
- native power management
- battery status
- backlight controls with smooth transitions, save/restore across restart
- accelerated graphics
- wired Ethernet
- Mac App Store working
- Messages/FaceTime, even though I didn't run through the guide 
- Blurtooth and wifi works powered by intwm.kext and Bluetoothinjector.kext
- Cardreader works with Sinetek-rtsx with add bootargh see on config.plist files



## My hackintosh Catalina 10.15.6 on HP Elitebook 850 G1


<img src="/images/PCI.png" width=600>


## Sources

- **1** [zxystd OpenIntelWireless](https://github.com/OpenIntelWireless/).
- **2** [RehabMan for hotpatch and more](https://github.com/RehabMan/HP-ProBook-4x30s-DSDT-Patch/).
- **3** [AcidanThera for lilu WhateverGreen](https://github.com/acidanthera/).
- **5** [CloverHackyColor for Clover BootLoader](https://github.com/CloverHackyColor/CloverBootloader/releases/).
- **6** [AcidanThera for OpenCore](https://github.com/acidanthera/OpenCorePkg)



