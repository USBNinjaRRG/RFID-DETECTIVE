# RFID-DETECTIVE

Portable RFID reader and analyzer supporting HF (MIFARE, NTAG) and LF (EM4100, T5577) cards.
Displays UID and card information on onboard OLED, with optional USB communication to desktop app.

## Features
- HF/LF card detection and UID display
- MIFARE Classic 1K key authentication
- OLED status interface
- Future: USB serial communication with PC

## Hardware
- MCU: STM32F103 (example)
- RFID: PN532 + LF module
- Display: SSD1306 OLED

## Software
- Firmware: C/C++ (STM32CubeIDE)
- Companion App: Python (PyQt5)

## License
Licensed under the MIT License.
