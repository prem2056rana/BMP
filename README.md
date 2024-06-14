
# BMP085 Temperature and Pressure Sensor with Arduino

## Overview

This project demonstrates how to use the BMP085 temperature and pressure sensor with an Arduino. The sensor readings (temperature in Celsius and pressure in Pascals) are printed to the serial monitor.

## Prerequisites

- **Hardware**:
  - Arduino board (e.g., Arduino Uno)
  - BMP085 temperature and pressure sensor
  - Connecting wires

- **Software**:
  - Arduino IDE
  - Adafruit BMP085 Unified library
  - Adafruit Sensor library

## Installation

1. **Set Up the Hardware**:
    - Connect the BMP085 sensor to the Arduino using I2C:
      - VCC to 3.3V (or 5V, depending on your sensor)
      - GND to GND
      - SDA to A4 (on Arduino Uno)
      - SCL to A5 (on Arduino Uno)

2. **Install the Required Libraries**:
    - Open the Arduino IDE.
    - Go to **Sketch** > **Include Library** > **Manage Libraries**.
    - Search for "Adafruit BMP085 Unified" and install the library.
    - Search for "Adafruit Sensor" and install the library.

3. **Upload the Code**:
    - Copy the provided code into the Arduino IDE.
    - Select the appropriate board and port from the **Tools** menu.
    - Click the **Upload** button.

## Usage

1. **Open the Serial Monitor**:
    - After uploading the code, open the Serial Monitor from the Arduino IDE (**Tools** > **Serial Monitor**).
    - Set the baud rate to 9600.

2. **View the Output**:
    - The Serial Monitor will display the current temperature and pressure readings from the BMP085 sensor.

