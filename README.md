# Hackintosh-Opencore-HP-9470m-1600x900
Opencore EFI bootloader for HP 9470m with 1600x900 resolution

<p align="center">
  <img width="400" height="300" src="/img/HP_9470m.png">
</p>

# Specifications:
* CPU: Intel Core i5-3437U
* GPU: Intel HD Graphics 4000
* Resolution: 1600 x 900
* RAM: 8 GB
* Audio: IDT 92HD91BXX
* Wi-Fi: Intel® Centrino® Advanced-N 6235
* Bluetooth: Intel Bluetooth 4.0
* Ethernet: Intel 82579LM
* Touchpad: Synaptics SMBus TouchPad
* Card reader:
  - JMicron Card Reader
  - Alcor Micro USB Smart Card Reader
* Fingerprint: Synaptics Fingerprint Sensors

# Opencore version: 
0.6.1

# MacOS version:
macOS Catalina 10.15.6

# Working:
* Intel HD Graphics 4000
* Brightness
* Night shift
* Audio (VoodooHDA.kext)
* Internal microphone
* Touchpad (with full gestures like real Mac)
* Battery percentage (battery patch and ACPIBatteryManager.kext)
* Ethernet
* Bluetooth
* iCloud - Facetime - iMessage - Siri
* Card reader
* CPU power management (SSDT-PM.aml)
* Webcam (it not works with MacBookAir or MacBookPro SMBIOS)
* All USB ports

# Not working:
* Intel® Centrino® Advanced-N 6235
* External microphone
* Synaptics Fingerprint Sensors

# SMBIOS:
iMac16,1

# Note:
Don't use this EFI bootloader for 1366x768 resolution

# Screenshots:
<p align="center" style="margin:20px">
  <img src="/img/Properties.png" alt="System Information">
</p>
<p align="center" style="margin:20px">
  <img align="center" src="/img/Backlight.png">
</p>
<p align="center" style="margin:20px">
  <img align="center" src="/img/Touchpad_1.png">
</p>
<p align="center" style="margin:20px">
  <img align="center" src="/img/Touchpad_2.png">
</p>
<p align="center" style="margin:20px">
  <img align="center" src="/img/Touchpad_3.png">
</p>
