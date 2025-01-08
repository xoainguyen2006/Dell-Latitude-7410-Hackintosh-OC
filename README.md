# Dell-Latitude-7410-Hackintosh-OC
OpenCore based EFI for Dell Latitude 7410

![Dell-Latitude-7410-Hackintosh](https://github.com/user-attachments/assets/e016d9fa-944b-46a4-8040-290f9689befb)

I am currently using macOS Ventura 13.7.1 and I wouldn't recommend updating to Sonoma because of the issues with the iServices due to Wifi kext so wait until it's fixed. 

## System Configuration

- CPU:  Intel Core i7-10610U
- iGPU: Intel UHD Graphics 630 (Comet Lake)
- RAM:  32GB DDR4 2667Mhz
- SSD:  512 GB Intel 660P NVMe 
- WiFi: Intel® Wi-Fi 6 AX201
- Display: 14" 1920*1080 FullHD IPS
- Sound Card: Realtek ALC295

### BIOS Version

1.36.0


### Bootloader

OpenCore 1.0.0

### SMBIOS

MacBookPro16,2

### SecureBootModel 
j215

## BIOS Settings

- Boot mode: UEFI
- Fast Boot: Thorough
- SecureBoot: Disable
- SATA Mode: AHCI 

## What's working

 
 - [x] CPU Speedstep

 - [x] iGPU acceleration

 - [x] Battery Management
 
 - [x] Sleep/Wake
 
 - [x] Internal Speakers
 
 - [x] Internal Microphone
 
 - [x] Audio Jack - Working with ComboJack - [https://github.com/macos86/ComboJack](https://github.com/macos86/ComboJack)
 
 - [x] WiFi (2.4Ghz + 5Ghz)
 
 - [x] Bluetooth

 - [x] HDMI + audio over HDMI (I didn't test it)

 - [x] Touchpad with Gestures + Buttons

 - [x] Web Camera

 - [x] USB 3.0

 - [x] MicroSD card reader 

 - [x] Native hotkeys support with Fn keys (Volume Fn+F2/F3 and Screen Brightness Fn + F6/F7)
 
 - [x] USB-C charging

 - [x] USB-C DP-alt Mode
  
 - [x] USB-C Data transfer
 
 - [x] Thunderbolt (needs to plug a device before boot)
    
 - [x] iServices (iMessage & FaceTime)
 

## What's not working

- Everything is working great so far!

## What's not tested yet

- HDMI
- Thunderbolt

## Additional Notes

Use one-key-hidpi to fix display scaling [https://github.com/xzhih/one-key-hidpi](https://github.com/xzhih/one-key-hidpi) <br>
Don't forget to map your USB ports [https://github.com/corpnewt/USBMap](https://github.com/corpnewt/USBMap) <br>
Don't forget to generate your own SMBIOS before installing macOS [https://github.com/corpnewt/GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)

- ENJOY!
