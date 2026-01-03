# 🦖 ESP32 Dino Run — v1.9.5 (Mini-Cactus Edition)

An advanced version of the classic "Dino Run" arcade game, optimized for the **ESP32** microcontroller and **SSD1306 OLED** display. This project has evolved from a simple clone into a feature-rich game with survival mechanics and progressive difficulty.

## ✨ Key Features
- **3 HP System:** Players have three lives, allowing for a more forgiving and engaging experience.
- **Recovery Mechanic:** Collect 5 hearts to restore 1 life (up to a maximum of 3 HP).
- **Multi-Height Obstacles:** Cacti can now appear on the ground or fly at different altitudes, requiring timed jumps.
- **Invincibility Frames:** 1 second of protection after taking damage, indicated by a flashing sprite.
- **High Score Persistence:** Your best score is saved to the ESP32's NVS memory using `Preferences.h`.
- **Chrome Style Graphics:** Custom-drawn sprites inspired by the original Google Chrome Dino game.

## 🛠 Hardware Requirements
- **Microcontroller:** ESP32 (DevKit V1)
- **Display:** 0.96" SSD1306 OLED (I2C 128x64)
- **Button:** Tactile push button (Connected to GPIO 15)
- **Sound:** Active or Passive Buzzer (Connected to GPIO 25)

## 🔌 Wiring Diagram
| Component | ESP32 Pin |
|-----------|-----------|
| OLED SDA  | GPIO 21   |
| OLED SCL  | GPIO 22   |
| Button    | GPIO 15   |
| Buzzer    | GPIO 25   |



## 🚀 Installation
1. Install **Arduino IDE**.
2. Install the following libraries via Library Manager:
   - `Adafruit SSD1306`
   - `Adafruit GFX Library`
3. Flash the `.ino` file to your ESP32.

## 👨‍💻 Author
**AndiBond**
