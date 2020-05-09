# ASRock Z370M-ITX/ac macOS Catalina
A working OpenCore configuration for ASRock Z370M-ITX/ac
<br>
Get updates through your email by clicking the watch button!

## Configuration change logs
See here: https://github.com/replecta/Z370M-ITX-ac-macOS-OpenCore/blob/master/CHANGELOG.md

## macOS version
`10.15.4 (19E287)`

## System Specs
* Motherboard: ASRock Z370M-ITX/ac
* CPU: Intel i7-8700K 3.7GHz
* RAM: Unknown brand 24GB (8GB and 16GB) DDR4-2400 Memory
* Storage: Samsung EVO Plus 970 500GB + Seagate 2TB 7200RPM HDD
* GPU: AMD Sapphire RX570 4GB + Intel UHD 630
* PSU: Corsair SF 450W 80+ Gold Certified Fully-Modular SFX Power Supply
* Wifi + BT: BCM94360CS2 with adapter

## Note
* As a personal preference, this configuration will boot into macOS immediately!<br>
  If you want to choose which disk you want to boot as! Press Option(Alt) key to show boot selector, alternatively you can edit the configuration file and turn `Misc > Boot > ShowPicker` to `YES/True`

## Post-install
* SmUUID and Serial Number generation for iMessage. Search the forums!<br>
Use [ProperTree](https://github.com/corpnewt/ProperTree) to edit plist files! Softwares such as OpenCore Configurator corrupts the file!

## Optional
* Turn iGPU dual monitor on in BIOS to use Sidecar with AMD GPU or any other compatible external GPU

## Working
* Dual GPU (EGPU + iGPU)
* Ethernet
* Sleep (Not fully tested)
* Audio
* Sidecar (You may need compatible Wifi and Bluetooth module and working iGPU)

The motherboard's built-in Bluetooth and Wifi module does NOT work with macOS.
You will need to get a compatible module for the M.2 slot, or use a USB
Bluetooth dongle.

## Issues or Bug reporting
Make an issue if you find a bug or a problem specifically for this hardware. Also if you found the solution, pull requests are welcome!

## Credits
- [acidanthera](https://github.com/acidanthera)
- [vit9696](https://github.com/vit9696)
