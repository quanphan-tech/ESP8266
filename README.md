## Hardware
- ESP8266 (NodeMCU)
- DHT11 sensor
- I2C LCD 16x2
- Jumper wires

## Wiring
| DHT11 | ESP8266 |
|------|--------|
| VCC  | 3.3V   |
| GND  | GND    |
| DATA | D3     |
| SCL | D1     |
| SDA | D2     |

## Features
- Read temperature & humidity
- Display data on LCD
- Real-time monitoring

## Setup

Install Arduino IDE
Add ESP8266 board
Install libraries:
- BlynkSimpleEsp8266
- DHT sensor library
- LiquidCrystal_I2C
Upload code

## Result
Temp: 28°C  
Humidity: 60%
