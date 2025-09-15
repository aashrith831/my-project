# my-project
This project is based on IOT and microcontroller called arduino.
# Arduino Temperature Monitor with LCD (I2C) and Buzzer

This project uses an **Arduino**, a **DHT11 temperature sensor**, a **16x2 LCD with I2C module**, and a **buzzer** to monitor temperature.  
The system displays the current temperature on the LCD and triggers a buzzer alarm if the temperature exceeds **40°C**.

---

## 🛠 Components Required
- Arduino Uno (or compatible board)  
- DHT11 Temperature & Humidity Sensor  
- 16x2 LCD Display with I2C Backpack (address: `0x3F`)  
- Buzzer (active buzzer recommended)  
- Jumper wires  
- Breadboard  

---

## ⚡ Circuit Connections

### DHT11 Sensor
- VCC → 5V  
- GND → GND  
- DATA → Pin **2**  

### LCD with I2C Module
- VCC → 5V  
- GND → GND  
- SDA → A4 (Arduino Uno)  
- SCL → A5 (Arduino Uno)  

### Buzzer
- Positive (+) → Pin **8**  
- Negative (–) → GND  

---

## 💻 Arduino Libraries Needed
Make sure you install these libraries in the Arduino IDE:
- [**LiquidCrystal_I2C**](https://github.com/johnrickman/LiquidCrystal_I2C)  
- [**Adafruit DHT Sensor Library**](https://github.com/adafruit/DHT-sensor-library)  
- [**Adafruit Unified Sensor**](https://github.com/adafruit/Adafruit_Sensor)  

---


