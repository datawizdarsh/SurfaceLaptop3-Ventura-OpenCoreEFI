# Surface Laptop 3 15" OpenCore EFI for macOS Ventura / Sonoma / Sequoia

<!-- add github tags here -->
![macOS](https://img.shields.io/badge/macOS-13.7-blue) ![macOS](https://img.shields.io/badge/macOS-14.4-blue) ![macOS](https://img.shields.io/badge/macOS-15.0-blue)
![OpenCore](https://img.shields.io/badge/OpenCore-1.0.1-9cf)

| **Surface Laptop 3 15"** | **macOS Ventura/Sonoma/Sequoia** |

## Features

* Running macOS Ventura 13.7 / Sonoma 14.4 / Sequoia 15.0 
* Support Bluetooth 4.0+ devices with the solution provided by [this issue](https://github.com/OpenIntelWireless/IntelBluetoothFirmware/issues/51). 

## Hardware

* **CPU**: Intel Core i7-1065G7
* **iGPU**: Intel Iris Plus Graphics G7
* **Memory**: 16 GB 3733 MHz LPDDR4X
* **Storage**: 256 GB NVMe SSD HFM256GDGTNG-87A0A
* **Display**: 15" 2496x1664

## Current status

| Component | Status | Notes |
| --------- | ------ | ----- |
| CPU | ✅ | |
| iGPU | ✅ | |
| Audio | ✅ | |
| USB | ✅ | |
| Touchpad | ✅ | |
| Keyboard | ✅ | |
| Battery | ✅ | |
| Bluetooth | ✅ | |
| Front camera | ✅ | Working with USB mapping. |
| Graphics Acceleration | ✅ | |
| WiFi | ✅ | Airdrop, Handoff, Sidecar are not working. This is a known issue for `itlwm`. |
| Touchscreen | ✅ | For multi-touch, you need to install IPTSDaemon. |
| Sleep | :white_check_mark: | Can sleep and wake up well thanks to [jlempen](https://github.com/jlempen/Surface-IceLake-macOS-Hibernation-Fix/tree/main)'s method. |


> Note: It is normal to have screen flickering during installation for Sonoma ONLY & Sonoma to Sequoia Update. Please install Ventura first then use Dortania guide to create Sonoma recovery - reinstall macOS and finally update to Sequoia using update in system settings.
> Check releases for updated EFIs



## Credits

* [Dortania](https://dortania.github.io/OpenCore-Install-Guide/) for the OpenCore guide.
* [OpenIntelWireless](https://openintelwireless.github.io) for the WiFi and Bluetooth solution.
* [Surface Pro 7 OpenCore EFI](https://github.com/badstorm/surface-pro-7-opencore) for the initial OpenCore configuration.
* [Surface Laptop 3 Opencore EFI](https://github.com/jc-bao/surface-laptop3-ventura) for other fixes & testing
