<div align="center">

# ⚡ LilyGo T-Dongle-S3 Firmware Collection ⚡

[![Platform](https://img.shields.io/badge/Platform-ESP32--S3-blue?style=for-the-badge&logo=espressif)](https://www.espressif.com/)
[![Device](https://img.shields.io/badge/Device-LilyGo%20T--Dongle-orange?style=for-the-badge&logo=arduino)](https://www.lilygo.cc/)
[![Collection](https://img.shields.io/badge/Type-Firmware%20Collection-green?style=for-the-badge)](https://github.com/kaliwinki-1)

*A curated collection of penetration testing and utility firmwares for the LilyGo T-Dongle-S3.*

[Report an Issue](https://github.com/kaliwinki-1/T-Dongle-S3-Firmware/issues) • [View Files](https://github.com/kaliwinki-1/T-Dongle-S3-Firmware/tree/main)

---
</div>

> [!IMPORTANT]
> **⚠️ DISCLAIMER & CREDIT / AVERTISSEMENT**
> 
> This repository is a **personal archive/collection**. I am **not** the author of these firmwares. 
> All credit goes to the brilliant developers listed below. Please support them by starring their original repositories!
> 
> *Ce dépôt est une collection personnelle. Je ne suis pas l'auteur de ces programmes. Tout le mérite revient aux créateurs originaux cités ci-dessous.*

---

## 📂 Included Projects / Projets Inclus

Here is the list of firmwares currently hosted in this repository. Click the **Original Source** to support the creators.

| 📦 Firmware / Folder | 📝 Description | 👤 Original Creator / Source |
| :--- | :--- | :--- |
| **USB Army Knife** | The ultimate Swiss Army Knife for the ESP32-S3. Includes WiFi attacks, BadUSB, and more. | [**0x01G0r** (GitHub)](https://github.com/0x01G0r/USB-Army-Knife) |
| **WiFiExe** | ESP32-S3 based BadUSB that allows remote payload execution via a web interface. | [**ravssh** (GitHub)](https://github.com/ravssh/WifiExe) |
| **UltraWiFiDuck** | Advanced BadUSB script injection (Ducky Script) over WiFi. Based on the famous WiFiDuck. | [**Spacehuhn** (GitHub)](https://github.com/spacehuhn/WiFiDuck) |
| **WHID-Master** | "WiFi HID Injector". Allows you to inject keystrokes remotely over WiFi. | [**WHID-Injector** (GitHub)](https://github.com/whid-injector/WHID) |

---

## 🚀 Quick Start Guide

Most of these firmwares come as `.bin` files or source code.

### 🔧 How to Flash (Generic Method)

1.  **Enter Boot Mode:**
    * Hold the **BOOT** button on your T-Dongle-S3.
    * Plug it into your USB port.
    * Release the button.
2.  **Flash:**
    * Use **[ESP Web Tool](https://web.esphome.io/)** (Chrome/Edge) or **[Esptool.py](https://github.com/espressif/esptool)**.
    * Select the `.bin` file from the folder you want to try.
    * Flash at offset `0x0` (unless specified otherwise in the folder's text file).

> [!TIP]
> Check the `.txt` or `README` files inside each specific folder for detailed instructions (WiFi passwords, default IPs, etc.).

---

## ⚖️ License & Rights

Each project in this collection is subject to its original license (MIT, GPL, etc.).
* If you are a developer and want your work removed from this collection, please **open an issue**, and I will remove it immediately.
* *Si vous êtes un créateur et souhaitez que votre projet soit retiré, ouvrez une issue et je le ferai immédiatement.*

---

<div align="center">

*Collection maintained by [kaliwinki-1](https://github.com/kaliwinki-1)* *Happy Hacking!* 🏴‍☠️

</div>
