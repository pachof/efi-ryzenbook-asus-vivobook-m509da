# <div align="center">EFI For Asus VivoBook M509da</div> 

## Bootloader and macOS Versions

| OpenCore  | macOS   |
| --------  | ------- |
|   1.0.3   | Monterey (Use SMBIOS ```MacBookAir8,2```) |

</div>

## Laptop Specification
 
|                     | Specifications| Note |
| ---------------------------- | ---------------------- |------------------|
| ``Chipset``| AMD Chipset |   |
| ``CPU``| OctaCore AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx 2.10 GHz|
| ``Memory``| 8GB DDR4 2400Mhz | 2 x 4GB DDR4. |
| ``iGPU``| Radeon Vega 8 Mobile Gfx |
| ``Fingerprint`` | ELAN FP Sensors | Not working in macOS. |
| ``Screen``| 15.6" 1920 x 1080 60 Hz |    |
| ``Ethernet``| No Ethernet |       |
| ``Wifi``| Realtek 8821 | Not Works, Use HoRNDIS | 
| ``Bluetooth``| Realtek 8821 | Not Works, Use HoRNDIS | 
| ``Audio``| Realtek ALC256 | Add `alcid=66` to boot-arg or add layout-id to DeviceProperties. |
| ``Touchpad``| Elan 1300 |
| ``Dimensions``| 360mm x 235mm x 22.9mm |     |
|``Weight``| 1.9kg |     |
  
<div align="center">
  
  
</div>

## Features

|                               | OpenCore             |
| ----------------------------- | -------------------- |
| ``Wifi and Bluetooth``|✅|
| ``Audio``|✅|
| ``Keyboard and Trackpad``|✅ except The Touchpad no works|
| ``Headphone Jack``|? No tested|
| ``Graphics``|✅|
| ``Battery``|✅|
| ``Card Reader``|? No tested|
| ``Power Management``|✅|
| ``Multigesture Trackpad``|❎ No works |                                 
| ``Webcam``|✅|
| ``USB Port``|✅|
| ``Facetime and iMessage``|? No tested|
| ``Sleep``|✅|
| ``Hotkeys``|✅|
