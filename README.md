# Acer_TraveMate_P249_hackintosh
Install Hackintosh(Big Sur & Catalina) in Acer TraveMate P249(i5-6200U)

## Configuration
* CPU: i5-6200U
* Memory: Hynix DDR4 2133MHz 8GB
* Hard Disk: Hikvision HS-SSD-C160 512G
* Wireless network card: Intel Wireless 7265

## BIOS Configuration
### 1. Reset BIOS to default configuration

### 2. Required configuration to install macOS
* BOOT
  * Secure Boot: Disabled

## Working status
* [x] CPU Frequency conversion, native power management
* [x] Nuclear display
* [x] Ethernet
* [x] WIFI ([zxystd Intel wireless network card driver developed by Great God](https://github.com/OpenIntelWireless/itlwm))
* [x] Bluetooth ([zxystd Intel Bluetooth driver developed by Great God](https://github.com/OpenIntelWireless/IntelBluetoothFirmware))
* [x] Sound card
* [x] Camera
* [x] touchpad
* [x] USB and USB extension
* [x] HDMI Output
* [x] Shut down, restart, sleep

## remind

* After the system is installed, please use OpenCore Configurator to generate the SMBIOS serial number, otherwise you will not be able to log in to the App Store

## Update log

| date       | Details                                                              |
|----------- |----------------------------------------------------------------------|
| 2021.08.11 | OpenCroe 0.7.2 & Big Sur 11.5.1 |
| 2021.07.06 | OpenCroe 0.7.1 |
| 2021.06.08 | OpenCroe 0.7.0 & Big Sur 11.4 |
| 2021.05.11 | OpenCroe 0.6.9 & Big Sur 11.3 |
| 2021.04.06 | OpenCroe 0.6.8 & Big Sur 11.2.3 |
| 2021.03.03 | OpenCroe 0.6.7 & Big Sur 11.2.2 |
| 2021.02.03 | OpenCroe 0.6.6 & Big Sur 11.2 |
| 2021.01.05 | OpenCroe 0.6.5 |
| 2020.12.08 | OpenCroe 0.6.4 & Big Sur 11.1 |
| 2020.11.03 | OpenCroe 0.6.3 & Big Sur 11.0.1 RC 1 |
| 2020.10.09 | OpenCroe 0.6.2 & Big Sur 11.0 Beta 9 |
| 2020.09.21 | move to OpenCroe 0.6.2 Beta |
| 2020.08.24 | Clover 5121 |
| 2020.08.13 | Clover 5120 |
| 2020.07.08 | Clover 5119 |
| 2020.06.02 | initial version |
