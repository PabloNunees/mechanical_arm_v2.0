# mechanical_arm_v2.0

Second version of a robotic arm project using ESP32, with Wi-Fi control, LCD interface and programmable motion sequences.

---

## Project Overview

This project consists of an improved robotic arm built with the ESP32 microcontroller. It allows:

- Manual control using potentiometers and buttons  
- LCD display interface via I2C  
- Wi-Fi communication between control and arm  
- Recording and automatic playback of motion sequences
  
---

## Technologies and Components

- ESP32 microcontroller  
- Servo motors for arm articulation  
- Potentiometers and buttons for user input  
- I2C LCD display for UI and feedback 
- External power supply for servos  

---

## Features in Version 2.0

-Servo control through potentiometers

-Interactive LCD display interface

-Save and replay sequences of movements

-Interpolated servo movements for smooth transitions

-Planned: remote control via Wi-Fi

-Planned: web interface for visualization and control

---

## Contributing

-Contributions are welcome. To contribute:

-Fork this repository

-Create a new branch with your feature or fix

-Commit your changes

-Open a pull request with a detailed description

---

## Getting Started

1. Clone the repository:
   
```bash
git clone https://github.com/PabloNunees/mechanical_arm_v2.0.git
cd mechanical_arm_v2.0
```

2.Install required tools:

-Arduino IDE or PlatformIO

-ESP32 board packages

-Required libraries (Servo, LiquidCrystal_I2C, etc.)

3.Open the project in your preferred environment and upload to the ESP32.

---

License
This project is licensed under the MIT License.

---

## Contributors

- [@PabloNunees](https://github.com/PabloNunees) – Main development
- [@acpnf](https://github.com/acpnf)

