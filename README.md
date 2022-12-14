# Hackintosh Asus X415FAC
[![Github release](https://img.shields.io/github/release/rizaldydeta/Hackintosh-Asus-X415FAC.svg?color=blue)](https://github.com/rizaldydeta/Hackintosh-Asus-X415FAC/releases/latest)
[![Github downloads](https://img.shields.io/github/downloads/rizaldydeta/Hackintosh-Asus-X415FAC/total.svg?color=blue)](https://github.com/rizaldydeta/Hackintosh-Asus-X415FAC/releases)
[![BIOS](https://img.shields.io/badge/BIOS-202-important.svg)](https://www.asus.com/supportonly/X415FAC/HelpDesk_BIOS/)
[![OpenCore Version](https://img.shields.io/badge/OpenCore-0.8.3-cyan.svg)](https://github.com/acidanthera/OpenCorePkg/releases/latest)
[![macOS Monterey](https://img.shields.io/badge/macOS-12.4-white.svg)](https://www.apple.com/macos/monterey/)
[![Release](https://img.shields.io/badge/Download-latest-success.svg)](https://github.com/rizaldydeta/Hackintosh-Asus-X415FAC/releases/latest)
[![Donate with PayPal](https://img.shields.io/badge/paypal-donate-red.svg)](https://paypal.me/rizaldydeta)

Hackintosh resources for Asus X415FAC

This is my complete EFI folder to be used for Hackintosh on Notebook Asus X415FAC

<p align="center">
  <img src="/images/X415fac-center.png?raw=true" width="400" height="400" alt="ASUS X415FAC Model">
</p>

### How to Get it?

- Open Terminal with Command: $ `git clone https://github.com/rizaldydeta/Hackintosh-Asus-X415FAC`
- Or Just [Clone](https://github.com/rizaldydeta/Hackintosh-Asus-X415FAC.git) / [Download](https://github.com/rizaldydeta/Hackintosh-Asus-X415FAC/releases/latest) with Specific Folder Only

--------------------------------------------------------------------------------------------

### Notebook Specs
<img src="/images/x415fac.png?raw=true" width="400" height="400" alt="Asus X41FAC" align="right">

- <b>Model</b>: Asus X415FAC
- <b>CPU</b>: Intel® Core™ i3-10110U
- <b>IGPU</b>: Intel UHD Graphics 630
- <b>RAM</b>: 8GB
- <b>Storage</b>: 1x Kingston NVME 256GB
- <b>Ethernet</b>: No Built-In Ethernet
- <b>WiFi</b>: Intel Wireless-AC 9560
- <b>Audio</b>: Realtek ALC256
- <b>Touchpad</b>: ELAN1200 I2C Interface
- <b>BIOS version</b>: X415FAC.202

--------------------------------------------------------------------------------------------

### EFI Contains
- <b>OpenCore Bootloader</b> binary, config.plist, drivers, themes, tools, etc..
- <b>Patched ACPI Tables (DSDT)</b> for Graphics, Audio, WiFi, Battery, Touchpad, etc..
- <b>3rd party kexts</b> for working devices under Mac OS Catalina 10.15.x upto macOS Ventura 13.x
 
--------------------------------------------------------------------------------------------
 
### What Worked
- [x] QE/CI Graphics Of IGPU UHD 630
- [x] Restart, Sleep and Shutdown
- [x] Internal Speaker, Headphone audio and Internal Mic
- [x] Brightness
- [x] Backlight keyboard
- [x] Touchpad
- [x] HDMI
- [x] HDMI Audio
- [x] Wifi
- [x] Bluetooth
- [x] Battery Indicator
- [x] All USB Ports
- [x] Function FN Keys
  - `FN` + `F1` - Volume Mute
  - `FN` + `F2` - Volume Down
  - `FN` + `F3` - Volume Up
  - `FN` + `F4` - Brightness Up
  - `FN` + `F5` - Brightness Down
  - `FN` + `F6` - Enable/Disable Touchpad
  - `FN` + `F7` - Keyboard Backlight Up/Down
 
--------------------------------------------------------------------------------------------
 
### Not Worked / Bugs
- [ ] Internal Webcam, just black output (Common Problem for VivoBook Series)
 
--------------------------------------------------------------------------------------------

### Credits
- [Apple](https://apple.com) for macOS.
- [Acidanthera](https://github.com/acidanthera) for OpenCore and the majority of the kexts.
- [Dortania](https://github.com/dortania) For great and detailed guides.
- [Rehabman](https://github.com/RehabMan) for contributing to most of the ACPI patching guides I used.
- [OpenIntelWireless](https://github.com/OpenIntelWireless) for intel wifi and bluetooth kexts.
- [Niraj Kumar Yadav](https://github.com/black-dragon74/ALCPlugFix-Swift) for combo jack audio patch.
- [Bao-Hiep Le](https://github.com/hieplpvip/AsusSMC) for patch Asus Laptops keyboard backlight and Fn keys.
- [Andres ZeroCross](https://github.com/andreszerocross) for simple patch HPET, RTC, TIMR, IPIC and Devices.
- [VoodooI2C](https://github.com/VoodooI2C/VoodooI2C) for touchpad i2c controller kexts.
- every other people that contributed to the hackintosh world.

--------------------------------------------------------------------------------------------

### If you need help please contact me on [Telegram](https://t.me/rizaldydeta)
 
