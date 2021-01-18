# Dell Vostro 3568 Hackintosh - OpenCore (Big Sur - 11.1)

Intro
---

![About this Mac](http://i.imgur.com/3Fg1zZp.png)

| | Version |
| ---: | :--- |
| ``OpenCore`` | 0.6.4 (RELEASE) |
| ``Big Sur`` | 11.1 (20C69) |

Hardware
---

**Dell Vostro 3568 - Kaby Lake**

| | Specifications | macOS Catalina & Big Sur Compatibility |
| ---: | :--- | :--- |
| ``Chipset`` | Intel Kaby Lake | No issues |
| ``CPU`` | Intel Core i7-7500U Processor, 2 Cores / 4 Threads, 2.7Hz / 3.5GHz, 4MB Cache | No issues |
| ``Memory`` | 8GB dual-channel DDR4-2133MHz, up to 16GB | No issues |
| ``GPU`` | Intel HD Graphics 620 | No issues |
| ``dGPU`` | AMD Radeon HD 8550M/R5 M230 (2GB GDDR3 VRAM) | Not support. Disable with boot-args `-wegnoegpu` |
| ``Storage`` | Samsung 860 EVO 250GB SSD + 1TB HDD | No issues |
| ``Screen`` | 15.6" Full HD 60Hz, 1920 x 1080 TN |  No issues |
| ``Webcam`` | Windows Hello built-in IR HD webcam (1MP / 720P) |  No issues. Windows Hello is not supported in macOS |
| ``Ethernet`` | RJ45 RTL8111 Realtek Ethernet | No issues |
| ``WiFi`` | Intel Wireless-AC 3165 | No issues, using [itlwm.kext](https://github.com/OpenIntelWireless/itlwm/releases) and [Heliport](https://github.com/OpenIntelWireless/HeliPort/releases) |
| ``Input & Output`` | USB 3.0 (USB-A) x3 | No issues |
| - | HDMI 1.4 | No issues |
| - | VGA | No issues |
| ``Soundboard`` | Realtek ALC256 (ALC3246) | No issues |
| ``Battery`` | 47WHr | About 3-5h after proper Power Management configuration. |
| ``Keyboard`` | - | No issues |
| ``Touchpad`` | Dell Touchpad | No issues. ACPI should be patched to enable gesture |
| ``Dimensions`` | 23.65mm x 260mm x 380mm | - |
| ``Weight`` | 2.29 kg | - |
| ``Power`` | 65W Power Adapter | - |
