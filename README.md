# 🏍 
ESP-CYB32BIKE

A vertical-scrolling arcade runner for the **Waveshare ESP32-S3-Touch-LCD-1.47**.  
Ride a neon-lit motorcycle down an infinite highway,
and collect data canisters — all controlled with nothing but the capacitive touchscreen.

---

## 📟 Hardware

| Item | Spec |
|---|---|
| **Board** | [Waveshare ESP32-S3-Touch-LCD-1.47](https://www.waveshare.com/esp32-s3-touch-lcd-1.47.htm) |
| **MCU** | ESP32-S3 (Dual-core Xtensa LX7, Wi-Fi + BLE) |
| **Display** | 1.47" IPS LCD, 172×320, JD9853 driver |
| **Touch** | AXS5106L capacitive controller (I²C) |
| **Flash** | 8 MB Quad SPI + 8 MB PSRAM |
| **Firmware** | CircuitPython 10.2.0 or newer |

> **Note:** The game uses **only** the built-in display and touch controller. 
> No extra buttons, wires, or sensors required.

---

## 🚀 Quick Start

### 1. Install CircuitPython

1. Download the latest **CircuitPython 10.2+** UF2 for 
   `waveshare_esp32_s3_touch_lcd_1_47` from [circuitpython.org/downloads](https://circuitpython.org/downloads).
2. Hold **BOOT** → press **RST** → release **BOOT** to enter download mode.
3. Flash the UF2 via USB or ESP Web Tools.
**- I used [io.serialflow.espflash](https://play.google.com/store/apps/details?id=io.serialflow.espflash)** on Android
### 2. Copy the game

Save the file from this repo as **`code.py`** in the root of the `CIRCUITPY` drive ~ 
ZER0 DEPENDENCIES! 



