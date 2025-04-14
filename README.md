# Project-on-the-Crypt
This project involves using a DHT11 temperature sensor and passive buzzer with an Arduino Uno board to simulate an ancient artifact that responds to breath by playing a melody. The goal is to cool the sensor to trigger melodies.
# Context
You are in a dark and mysterious room. In the middle, there is a strange object: a small crystal connected to a box that can play music.
On the crystal it is written:
“Only the breath of the stars will reveal the melody.”
You understand that this crystal is like a magic thermometer (the TMP36 sensor). He measures the temperature around him. If the air is too hot, it remains silent. But if you blow on it to cool it, it activates and plays a melody thanks to the sound box (the buzzer).
Challenge: blow on the sensor to lower the temperature and trigger the music!

# Necessary equipment

## The DHT11 module
![image](https://github.com/user-attachments/assets/0ace4fdc-a18f-40ec-b0c5-116233a9fe8b)

### Features 
Power supply: 3V to 5.5V  
Consumption: 0.5 mA nominal / 2.5 mA maximum
Temperature measurement range: 0°C to 50°C ± 2°C
Humidity measurement range: 20-90%RH ±5%RH
Size:15mm x 12mm x 5.5mm
Weight: 3g

## Arduino Uno 
Arduino Uno is a microcontroller board based on the ATmega328P.

![image](https://github.com/user-attachments/assets/7ac1187d-d48a-40df-bce6-43f1f234e987)

• Microcontroller: ATmega328P (8 bits, 16 MHz).

• Memory (32 KB flash memory, 2 KB RAM, 1 KB EEPROM memory).

• Inputs/Outputs (14 digital pins, 6 analog inputs).

• Power supply: 5V (via USB or external 7-12V power supply).

• Communication: USB port for programming and serial communication.

## Breadboard
![image](https://github.com/user-attachments/assets/3ee9cc5d-983f-429f-b13d-c6453c4be193)

## Cables
![image](https://github.com/user-attachments/assets/bcd6168c-daad-4920-8855-6d3bf8b5d7dd)

## Circuit assembly
DHT11 Sensor Connections
- Vout pin of the DHT11 → Pin 2 on the Arduino (to read the temperature).
- Vcc pin of DHT11 → 5V on the Arduino.
- GND pin of the DHT11 → GND on the Arduino.

Passive buzzer connections
- Positive pin of the buzzer → Pin 8 on the Arduino (to control the melody).
- Buzzer negative pin → GND on the Arduino.
![image](https://github.com/user-attachments/assets/42a67c32-4c94-4970-974e-145ffae27e19)
