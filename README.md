# CanSat Project

## Overview

This repository contains the code and documentation for our CanSat project, designed for participation in CanSat competitions. The CanSat is equipped with an Arduino-based Onboard Computer (OBC) and an ESP32-Cam for vision capabilities, making it an IoT project.

## Project Components

### 1. Arduino Mega

The Arduino Mega serves as the core of our Onboard Computer (OBC), managing and controlling various sensors and modules.

### 2. BMP180 (Weather Condition Measurements)

The BMP180 sensor is utilized for precise weather condition measurements during the CanSat's flight.

### 3. GY-271 (Magnetic Electronic Compass)

The GY-271 module provides accurate magnetic orientation data, contributing to the CanSat's navigation capabilities.

### 4. Neo M8 Series (GPS Module)

The Neo M8 series GPS module enables precise location tracking and contributes to the CanSat's overall navigation system.

### 5. GY-521 MPU6050 (Gyroscope)

The GY-521 MPU6050 gyroscope enhances the CanSat's stability and control by providing accurate orientation data.

### 6. ESP32-Cam

The ESP32-Cam module is responsible for the vision capabilities of the CanSat, leveraging internet connectivity for real-time image processing.

## Getting Started

### Prerequisites

- Arduino IDE installed
- [ESP32 Arduino Core](https://github.com/espressif/arduino-esp32) installed

### Installation

1. Clone this repository: `git clone https://github.com/Enzo-P/CanSat.git`
2. Open the Arduino IDE.
3. Load the Arduino sketch from the `src` directory.
4. Connect the CanSat hardware components as per the provided schematic.

### Usage

1. Upload the code to the Arduino Mega.
2. Power up the CanSat.
3. Monitor the CanSat's performance through the serial monitor in the Arduino IDE.
4. For ESP32-Cam functionality, follow additional instructions in the `esp32-cam/README.md` file.

---

Feel free to customize this template based on your project's specific details and requirements. Add more sections as needed, such as a troubleshooting guide, future enhancements, or a detailed project description.
