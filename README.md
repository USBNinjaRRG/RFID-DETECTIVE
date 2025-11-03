# 🛰️ RFID-DETECTIVE

**RFID-DETECTIVE** is a portable RFID reader and analyzer developed by **RRG (RFID Research Group)**.  
It supports both **HF (13.56 MHz)** and **LF (125 kHz)** RFID cards, with on-board display, MIFARE Classic password handling,  
and optional USB communication for PC integration.

---

## 🧭 Project Overview

The RFID-DETECTIVE device is designed to:
- Read and identify **different kinds of HF cards** (MIFARE, NTAG, DESFire, ISO14443).  
- Support **LF cards** (125 kHz EM4100 / T5577 / HID Prox).  
- Handle **MIFARE Classic 1K key authentication** (Key A/B).  
- Provide a **minimal user interface (MVP)** for on-device display of card UID and type.

This project aims to build a fully functional embedded firmware framework  
with a modular design that allows easy testing, debugging, and future feature expansion.

---

## 🧩 Development Documents

📘 **Main References**
- [🧾 Task Notes & Development Bounties](TASK-NOTES.md)
- [📄 Hardware Reference (coming soon)](docs/hardware.md)
- [⚙️ Firmware Setup Guide (coming soon)](docs/firmware-setup.md)

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-------------|
| **Microcontroller (MCU)** | STM32 / ESP32 (depending on version) |
| **RFID Modules** | PN532 (HF) and EM4100/T5577 (LF) |
| **Display** | OLED (SSD1306 / ILI9341) |
| **Language** | C / C++ |
| **Development Environment** | STM32CubeIDE / Arduino IDE / PlatformIO |

---

## 🧰 Current Development Focus
- [x] Hardware prototype assembled  
- [ ] HF card reading logic  
- [ ] LF card decoding  
- [ ] MIFARE 1K password implementation  
- [ ] UI display prototype  
- [ ] USB/Serial data communication  

Progress updates are tracked in the [Task Notes](TASK-NOTES.md).

---

## 🧑‍💻 Contributions

Interested engineers can contribute to specific functions listed in the [TASK-NOTES.md](TASK-NOTES.md) file.  
Please:
1. **Fork** the repository.  
2. Create a **feature branch** (e.g. `feature/hf-card-support`).  
3. Submit a **pull request (PR)** with details and a short demo or explanation.  

---

## 📇 Contact & Oversight

**Project Owner:** RFID Research Group (RRG)  
**Product Engineer (Overseeing Development):** Ambrose John Gbormie  
📧 **Technical Contact:** ambrose@rfidresearchgroup.com  

---

© 2025 RRG – RFID Research Group. All rights reserved.
