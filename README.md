# HP-350M_Laptop #
## EFI for Hackintosh Machine
If you have the Exact same Hardware configuration as like me you can use this EFI and also can use for verification purpose.

### If you are successful please consider donating via PayPal...
### That would be helpful for to keep creating!!

***DO NOT BLAME ME IF YOU HAVE DIFFERENT MACHINE AND MADE SOME MESS ON YOUR MACHINE ***

## Configuration is as follows ##
- Laptop : hp dv6 3127dx
- Intel Core i3 350M with Intel Integrated HD graphics 
- 2x 2 GB RAM at 1067 MHz
- HM55 Chipset
- Audio : Used VoodooHDA with AppleHDA Disabler kexts
- Realtek Ethernet 8111 Chipset
- WiFi Qualcomm Atheros 9285
- Synaptics trackpad
- PS/2 Ketboard

## what works: ##
- iGPU and Display works but VGA and HDMI ports are not tested
- Keyboard
- Audio
- Only 2 USB ports work
- Memory card reader
- Builtin speaker & Mic but 3.5 mm audio out and in port not tested.
- WiFi

## Doesn't work
- Brightness control (Cannot be fixed using SSDT-PNLF.aml)
- Booting without USB (Cannot fix using Duetpkg but the bootable USB works by using Duet pkg)
- Trackpad tap to click gesture
- Battery percentage
- Webcam

### youtube 
- link: https://www.youtube.com/watch?v=WnQPFkjuLTw

 ### Donate Me!!!
Consider Donating this will tremendously helpful for me
https://paypal.me/SanjayRavindran?locale.x=en_GB

### Credits:

- Thanks for [Apple](https://www.apple.com/ "Apple") For MacOs
- Thanks for [Acidantera](https://github.com/acidanthera "Acidantera") for OpenCore
- Thanks for [Dortania](https://dortania.github.io/OpenCore-Install-Guide/ "Dortania") for the Guide
- Thanks For [RehabMan](https://github.com/RehabMan "RehabMan") For Kexts
