<h1 align="center"> macOS on Toshiba Portege Z30-A-12X </h1>

<p align="center">
  <img src="https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh/blob/main/Resources/Images/macOS%20Toshiba%20Portege%20Z30.png">
</p>

<h4 align="center"> OpenCore config for Hackintosh Toshiba Portege Z30-A-12X </h4>

<p align="center">
<a href="https://www.apple.com/macos/monterey/">
  <img src="https://img.shields.io/badge/macOS-Monterey_v12.6.1-purple" width="215"/> </a>
<a href="https://github.com/acidanthera/OpenCorePkg/releases">
  <img src="https://img.shields.io/badge/OpenCore-0.8.5-9cf" width="155"/> </a>
<a href="https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh/releases">
  <img src="https://img.shields.io/badge/release-EFI-blue.svg" width="115"/> </a>
<a href="https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh/issues"> 
  <img src="https://img.shields.io/github/issues/yusufklncc/Toshiba-Portege-Z30-Hackintosh" width="145"/> </a>
<a href="https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh#changelog">
  <img src="https://img.shields.io/badge/Changelog-green.svg" width="105"/> </a>
</p>
<p align="center">
<a href="https://t.me/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-2CA5E0?logo=Telegram&logoColor=blue" width="150"/> </a>
<a href="https://www.youtube.com/c/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-red?logo=YouTube&logoColor=white" width="150"/> </a>
<a href="https://www.paypal.com/paypalme/sevenpay">
  <img src="https://img.shields.io/badge/-@sevenpay-2CA5E0?logo=PayPal&logoColor=red" width="140"/> </a>


## Contents
  - [Screenshots](https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh#screenshots)
  - [Original Hardware](https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh#original-hardware--)
  - [macOS Update History](https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh#macos-update-history)
  - [What's working](https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh#whats-working--)
  - [What's you have to do](https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh#whats-you-have-to-do--)
  - [Kexts Used](https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh#kexts-used)
  - [SSDTs Used](https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh#ssdts-used)
  - [Credits](https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh#credits)
  - [Donate](https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh#-donate---ba%C4%9F%C4%B1%C5%9F-)

## Screenshots

<p align="center">
  <img src="https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh/blob/main/Resources/Images/macOS%20Screenshots/About%20This%20Mac%20-%20Monterey.png">
</p>
  
### CPU Temperature  
- Minimum and Maximum

  <img src="https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh/blob/main/Resources/Images/Min%20CPU%20Frequency%20and%20Temperature.png" width="300">

  <img src="https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh/blob/main/Resources/Images/Max%20CPU%20Frequency%20and%20Temperature.png" width="300">
  
### Geekbench
- CPU
<p align="center">
  <img src="https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh/blob/main/Resources/Images/CPU%20Geekbench.png" width="500"/> </a>
</p>
  
- OpenCL
<p align="center">
  <img src="https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh/blob/main/Resources/Images/OpenCL.png" width="500"/> </a>
</p>

<details>
<summary>Monterey</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh/blob/main/Resources/Images/macOS%20Screenshots/macOS%20Monterey.png">
</p>
</details>
  
<details>
<summary>Big Sur</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh/blob/main/Resources/Images/macOS%20Screenshots/macOS%20Big%20Sur.png">
</p>
</details>

<details>
<summary>Bluetooth</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh/blob/main/Resources/Images/Bluetooth.png">
</p>
</details>

<details>
<summary>System Preferences</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Toshiba-Portege-Z30-Hackintosh/blob/main/Resources/Images/System%20Preferences.png">
</p>
</details>


## Original Hardware  💻

Type | Spec | Status
:---------|:---------|:----------
Model Name      | Toshiba Portege Z30-A-12X | ✅
CPU              | Intel(R) Core(TM) i5-4200U CPU @ 2.60GHz Haswell | ✅
RAM           | 8 GB 1600 MHz DDR3L | ✅
Internal Graphics Card | Intel(R) HD Graphics 4400 (1 GB) | ✅
Wi-Fi             | Intel Dual Band Wireless AC 3160 | ✅
Ethernet          | Intel I218-V | ✅
Audio       | Realtek ALC283 | ✅
Touchpad | ALPS PS/2 Pointing Device | ✅
SD Card Reader | RTS5227 PCI Express Card Reader  | ✅
Fingerprint | ?? | ❌
Display | ?? | ✅
Camera | Toshiba Webcam | ✅

## macOS Update History
- ✅ macOS Monterey 12.6.1
- ✅ macOS Monterey 12.4
- ✅ macOS Monterey 12.3.1
- ✅ macOS Monterey 12.3
- ✅ macOS Big Sur 11.6.3
- ✅ macOS Big Sur 11.0.1
- ✅ macOS Catalina 10.15.7
- ✅ macOS Mojave 10.14.6
- ✅ macOS High Sierra 10.13.6
- ✅ macOS Sierra 10.12.6
- ✅ macOS El Capitan 10.11.6

## What's working  💻
  
Type | Status
:---------|:---------
Turbo boost and CPU frequency stage |  ✅  
Intel HD Graphics 4400              |  ✅  
Brightness control                  |  ✅  
HDMI                                |  ✅  
Audio Realtek ALC283            |  ✅  
Intel Ethernet I218-V            |  ✅  
Intel AC 3160 Wi-Fi, Bluetooth, iServices...         |  ✅  
USB 3.0 (with Port Map)        |  ✅  
Touchpad (14 gestures are working)   |  ✅  
Battery status   |  ✅  
Camera   |  ✅  
S3 Sleep / Wake   |  ✅  
S4 Hibernation / Wake   |  ✅  
Shutdown / Reboot   |  ✅  
Fn shortcut keys   |  ✅  

## What's you have to do  💻
  
Type | Info | Status
:---------|:---------|:----------
SMBIOS Settings  | With [GenSMBIOS] you should definitely set your SMBIOS settings and ROM value for iCloud and Apple services. ROM value is your ethernet MAC address. Be sure your ethernet is en0 in Hackintool. |  ⚠️


## Kexts Used 
 
Kext | Info 
:---------|:---------
[Lilu](https://github.com/acidanthera/Lilu) | An open source kernel extension bringing a platform for arbitrary kext, library, and program patching throughout the system for macOS.
[VirtualSMC](https://github.com/acidanthera/VirtualSMC) | Advanced Apple SMC emulator in the kernel. Requires Lilu for full functioning.
[WhateverGreen](https://github.com/acidanthera/WhateverGreen) | Various patches necessary for certain ATI/AMD/Intel/Nvidia GPUs. This is needed for Intel HD 620.
[SMCBatteryManager](https://github.com/acidanthera/VirtualSMC) | a member of VirtualSMC that parses battery info.
[SMCProcessor](https://github.com/acidanthera/VirtualSMC) | a member of VirtualSMC that provides power info of processor temperature.
[AppleALC.kext](https://github.com/acidanthera/AppleALC) | An open source kernel extension enabling native macOS HD audio for not officially supported codecs without any filesystem modifications.
[USBPorts](https://www.youtube.com/watch?v=rlTDHkPzjAk&t=654s) | [USB] Kext to inject mapped USB Ports. (via Hackintool)
[CPUFriend](https://github.com/acidanthera/CPUFriend) | A Lilu plug-in for dynamic power management data injection.
[CPUFriendDataProvider](https://github.com/acidanthera/CPUFriend) | A CPUFriend plug-in for CPU power management.
[VoodooPS2Controller](https://github.com/acidanthera/VoodooPS2) | Contains updated Voodoo PS/2 Controller, improved Keyboard & Synaptics TouchPad.
[IntelMausi](https://github.com/acidanthera/IntelMausi) | [Ethernet] Intel onboard LAN driver for macOS.
[AirportItlwm](https://github.com/OpenIntelWireless/itlwm) | [Wi-Fi] An Intel Wi-Fi Adapter Kernel Extension for macOS.
[ToshibaBluetooth](https://www.tonymacx86.com/threads/bluetooth-is-not-detected-in-hackintool-or-system-report.318629/page-7#post-2331092) | [Bluetooh] This kext for toshiba. (thanks idragon81 from tonymacx86)
[IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | [Intel Bluetooth] Kernel Extension that uploads Intel Wireless Bluetooth Firmware to provide native Bluetooth in macOS.
[BlueToolFixup](https://github.com/acidanthera/BrcmPatchRAM) | [Bluetooth] Injecting bluetooth firmware on Monterey+.
[IntelBTPatcher](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | [Intel Bluetooth] A Lilu base patcher that fix Intel Bluetooth on Bigsur, Catalina, Mojave, High sierra etc, tested with Bigsur and Catalina all working good.
[IntelBluetoothInjector](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | [Intel Bluetooth] Injecting intel bluetooth firmware on Big Sur-.
[Sinetek-rtsx](https://www.insanelymac.com/forum/topic/321080-sineteks-driver-for-realtek-rtsx-sdhc-card-readers/page/2/#comment-2376387) | This driver is for Realtek SDHC card readers on a pci/pcie bus, most commonly found in laptops.
[NVMeFix](https://github.com/acidanthera/NVMeFix) | [SSD] NVMeFix is a set of patches for the Apple NVMe storage driver, IONVMeFamily.
[RTCMemoryFixup](https://github.com/acidanthera/RTCMemoryFixup#rtcmemoryfixup) | An open source kernel extension providing a way to emulate some offsets in CMOS (RTC) memory. It can help you to avoid some conflicts between macOS AppleRTC and firmware/BIOS of your PC.
[RestrictEvents](https://github.com/acidanthera/RestrictEvents) | Lilu Kernel extension for blocking unwanted processes causing compatibility issues on different hardware and unlocking the support for certain features restricted to other hardware.
[FeatureUnlock](https://github.com/acidanthera/FeatureUnlock) | Lilu Kernel extension for enabling: Sidecar, NightShift, AirPlay to Mac, Universal Control.
[NoTouchID](https://github.com/al3xtjames/NoTouchID) | Lilu plugin for disabling Touch ID support.


## SSDTs Used
  
SSDT | Info | Status
:---------|:---------|:---------
[SSDT-PTSWAK.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/04_Fixing_Sleep_and_Wake_Issues/PTSWAK_Sleep_and_Wake_Fix) | Comprehensive Sleep and Wake Patch. | [Functional]
[SSDT-AC.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/AC_Adapter_(SSDT-AC)) | Attaches an AC Adapter Device existing in a Laptop's DSDT to the AppleACPIACAdapter service in the IORegistry of macOS. | [Cosmetic]
[SSDT-EC-USBX.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/ec-fix.html#fixing-embedded-controller-ssdt-ecusbx) | Adds a fake Embedded Controller (SSDT-EC) and enables USB Power Management (SSDT-EC-USBX). | [Functional]
[SSDT-GPRW](https://dortania.github.io/OpenCore-Post-Install/usb/misc/instant-wake.html) | macOS will instant wake if either USB or power states change while sleeping. To fix this we need to reroute the GPRW/UPRW/LANC calls to a new SSDT. | [Functional]
[SSDT-HPET.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/irq.html#fixing-irq-conflicts-ssdt-hpet-oc-patches-plist) | Fixes IRQ conflicts. Required for on-board sound to work. | [Functional]
[SSDT-OC-XOSI.aml](https://dortania.github.io/Getting-Started-With-ACPI/ssdt-methods/ssdt-prebuilt.html#trackpad) | OS Check Fix patch to simulate a version of Windows for Darwin. | [Functional]
[SSDT-PLUG.aml](https://dortania.github.io/Getting-Started-With-ACPI/Universal/plug.html#fixing-power-management-ssdt-plug) | Allow the kernel's XCPM(XNU's CPU Power Management) to manage CPU's power management. | [Functional]
[SSDT-PNLF.aml](https://dortania.github.io/Getting-Started-With-ACPI/Laptops/backlight.html) | Adds Backlight Control for Laptop Screens. | [Functional]
[SSDT-SLPB.aml](https://github.com/5T33Z0/OC-Little-Translated/tree/main/01_Adding_missing_Devices_and_enabling_Features/Power_and_Sleep_Button_(SSDT-PWRB:SSDT-SLPB)) | Enabling Sleep Button. | [Functional]



## Credits
  
 - [Dortania](https://dortania.github.io) for developing OpenCore.
 - [Apple](https://www.apple.com) for macOS.
 - [Acidanthera](https://github.com/acidanthera) for most of the kexts.
 - [RehabMan](https://github.com/RehabMan) for battery patches.
 - [Sniki](https://github.com/Sniki) for USB kext.
 - And anyone else that helped to develop and improve hackintoshing.

<h1 align="center"> Donate - Bağış </h1>
<p align="center">
<a href="https://github.com/yusufklncc/yusfklncc/blob/main/Donate%20-%20Ba%C4%9F%C4%B1%C5%9F.md">
  <img src="https://github.com/yusufklncc/yusfklncc/blob/main/Resources/Donate.png" width="300">
