# 🧾 RFID-DETECTIVE Task Notes

This document outlines the **development plan and contribution tasks** for the **RFID-DETECTIVE** project —  
a portable RFID reader and analyzer built by **RRG (RFID Research Group)**.  
It covers the four main functional goals, workflow, and contribution details.

---

## 🧩 Core Functional Modules

| # | Function / Feature | Description | Est. Price (USD) |
|:-:|--------------------|--------------|-----------------:|
| 1 | 🔌 **HF Card Reading Support** | Implement reading of various high-frequency (13.56 MHz) cards — e.g., MIFARE Classic 1K/4K, NTAG, DESFire, ISO14443-A/B. | **$150** |
| 2 | 📡 **LF Card Reading Support** | Add support for low-frequency (125 kHz) cards — e.g., EM4100, T5577, HID Prox. | **$130** |
| 3 | 🔐 **MIFARE Classic 1K Password Handling** | Integrate Key A / Key B authentication for MIFARE Classic 1K cards and enable secure sector data access. | **$100** |
| 4 | 🖥️ **MVP User Interface** | Develop a simple on-device interface (OLED/LCD) to display card UID, type, and status. | **$120** |

💰 **Total Estimated Budget:** ≈ **$500**

---

## 🛠️ Contribution Workflow

1. **Fork this repository** and create a branch for your chosen task.  
2. Implement your feature and **submit a pull request (PR)**.  
3. Include short notes or a video demo of functionality.  
4. Upon successful review → merge → payment via milestone.

---

## 🧭 Future Enhancements
- 🔋 Battery monitoring and power management  
- 🔄 USB / Bluetooth connection to desktop software  
- 🧱 Enclosure design and 3D model  
- 💾 Optional data logging for UID history  

---

## ⚙️ Hardware Access Notes

Firmware developers should have access to one of the following:
- An **RFID-DETECTIVE prototype** device  
- Or a **compatible setup** (e.g., STM32F103 + PN532 + SSD1306 OLED)

Software and documentation contributors **do not need hardware access** —  
sample data and serial logs will be provided for simulation.

---

## 📇 Contact & Oversight

**Project Owner:** RFID Research Group (RRG)  
**Product Engineer (Overseeing Development):** Ambrose John Gbormie  
📧 **Technical Contact:** ambrose@rfidresearchgroup.com  

---

© 2025 RRG – RFID Research Group. All rights reserved.
