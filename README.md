# 🖥️ Raspberry Pi Pico W – SSD1306 OLED Display (MicroPython)

This project demonstrates how to interface an **SSD1306 OLED (128x64)** with the **Raspberry Pi Pico W** using **MicroPython** over the **I²C protocol**.

---

## 🧰 Requirements
- Raspberry Pi Pico W  
- SSD1306 OLED display (I²C version)  
- MicroPython firmware installed  
- Thonny IDE  

---

## ⚙️ Pin Configuration
| OLED Pin | Pico Pin | Function |
|-----------|-----------|----------|
| VCC | 3.3V | Power |
| GND | GND | Ground |
| SDA | GPIO16 | Data |
| SCL | GPIO17 | Clock |

---

## 🚀 How It Works
- The Pico communicates with the OLED using I²C bus 0.  
- The `ssd1306` MicroPython driver handles low-level display operations.  
- The display is cleared and refreshed every second, showing `"Hello World"`.

---

## 🧩 Code Features
- Adjustable I²C pins and address  
- Simple text rendering  
- Example base for sensor data display or menu UI  

---

## 🔧 Ideas to Extend
- Display temperature/humidity readings (DHT11/DHT22).  
- Add scrolling text or animations.  
- Create a mini dashboard (Wi-Fi status, time, etc.)  
