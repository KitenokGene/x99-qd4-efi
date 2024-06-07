# X99-QD4 OpenCore EFI
This build works on Sonoma

## PC Specifications
- Motherboard: Huananzhi X99-QD4
- CPU: Intel Xeon E5-2680v4
- GPU: NVIDIA GeForce GT 710
- SSD: ADATA SU650

## What works
- System
- GUI in OpenCore boot menu
- Graphics acceleration
- 144hz refresh rate over HDMI
- Ethernet
- USB devices
- iServices (change config.plist)

## Notes
- You should change MLB, ROM, SystemProductName, SystemSerialNumber and SystemUUID in config.plist. Refer to [OpenCore manual](https://dortania.github.io/OpenCore-Install-Guide/config.plist/)
- This build was tested on Monterey, Ventura and Sonoma.
- NVIDIA Kepler graphics acceleration works with [OpenCore Legacy Patcher](https://dortania.github.io/OpenCore-Legacy-Patcher/).
