# Hackintosh Catalina 10.15.6 on my HP Elitebook 850 G1

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

<img src="/images/furqonicmac.png" width=600>

<img src="/images/Networks.png" width=600>

<img src="/images/PCI.png" width=600>

<img src="/images/grfix.png" width=600>

<img src="/images/webcam.png" width=600>

<img src="/images/Ethernet.png" width=600>

<img src="/images/changewifissid.png" width=600>

<img src="/images/bluetooth.png" width=600>




## Sources

- **4** [zxystd OpenIntelWireless](https://github.com/OpenIntelWireless/).
- **4** [RehabMan for hotpatch and more](https://github.com/RehabMan/HP-ProBook-4x30s-DSDT-Patch/).
- **4** [AcidanThera for lilu WhateverGreen](https://github.com/acidanthera/).
- **4** [CloverHackyColor for Clover BootLoader](https://github.com/CloverHackyColor/CloverBootloader/releases/).

## 🤜🏻🤛🏻 For Support

You can support me and [buy me a coffee][8], if you want. 🙏🏻

[![ME Furqonic](https://img.shields.io/badge/SUPPORT-ME-succsess.svg?style=flat)](Support)
<br>
[![Paypal Furqonic](https://img.shields.io/badge/$-Paypal-informasional.svg?style=flat)](https://paypal.me/caturmahdialfurqon)
<br>
[![BSC Furqonic](https://img.shields.io/badge/ETH-0x07Fe74030B01B1F9A9c2699929d7CAFDa66Ebf06-informational.svg?style=flat)](https://etherscan.io/address/0x07Fe74030B01B1F9A9c2699929d7CAFDa66Ebf06)
<br>
[![BTC Furqonic](https://img.shields.io/badge/BTC-bc1qf8d3fcl4zf08qy3ecz8jyw3cf8y8urd0s2g32s-informational.svg?style=flat)](https://pastebin.com/raw/Z57X2iwX)
<br>
[![DOGE Furqonic](https://img.shields.io/badge/SOL-73hvmQLGmfxXiJqvqiG2MwZReC9H3tFusZJGfffrBHpy-informational.svg?style=flat)](https://pastebin.com/raw/Z57X2iwX)
<br>
[![LTC Furqonic](https://img.shields.io/badge/MATIC-0x07Fe74030B01B1F9A9c2699929d7CAFDa66Ebf06-informational.svg?style=flat)](https://pastebin.com/raw/Z57X2iwX)

<br>



