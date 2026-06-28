# Raspberry Pi Projects

A collection of hardware and software projects built with a Raspberry Pi 3B,
developed during summer 2026 as part of self-directed learning in electronics,
programming, and engineering.

## Hardware
- Raspberry Pi 3B (2015)
- BME280 temperature, humidity and barometric pressure sensor
- SG90 servo motors
- HC-SR04 ultrasonic distance sensor
- HC-SR501 PIR motion sensor
- SSD1306 OLED display
- Various LEDs, resistors, buttons and breadboards

## Projects

| Project | Description | Skills |
|---|---|---|
| Weather Station | BME280 sensor reading temp, humidity, pressure via I2C | GPIO, I2C, Python |
| Overnight Logger | CSV logging of weather data every 30 seconds | File I/O, datetime |
| Data Visualisation | Matplotlib graphs from overnight CSV data | Data analysis, matplotlib |
| Flask Dashboard | Live sensor data hosted as a local web server | Flask, HTTP, threading |

## Setup
```bash
python3 -m venv ~/pienv
source ~/pienv/bin/activate
pip install adafruit-circuitpython-bme280 matplotlib flask
```

## Author
Zakariyah — London, 2026