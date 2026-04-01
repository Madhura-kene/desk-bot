# desk_bot — chi's OLED Edition

ESP32-based animated OLED controller with a WiFi web interface.

## Hardware
- ESP32 Dev Module (30-pin)
- SSD1306 128x64 I2C OLED display

## Wiring
| OLED Pin | ESP32 Pin |
|----------|-----------|
| GND      | GND       |
| VCC      | 3V3       |
| SCL      | GPIO 22   |
| SDA      | GPIO 21   |

## Libraries Required
- Adafruit SSD1306
- Adafruit GFX Library

## Features
- Animated eye expressions (normal, squish, round, sad, dizzy, heart, freaky)
- IST Clock with browser sync
- Stopwatch
- Pixel canvas drawable from browser
- WiFi Access Point — connect and control from any phone/PC

## Usage
1. Flash `desk_bot.ino` to your ESP32
2. Connect to the WiFi AP shown on the OLED screen
3. Open `http://192.168.4.1` in your browser
```
