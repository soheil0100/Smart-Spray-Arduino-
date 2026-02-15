# Smart Spray Automation System

An automatic spray control system built using Arduino.  
This system activates a spray mechanism based on sensor input and predefined timing logic.

---

## Overview

The Smart Spray System is designed to automate liquid spraying processes.  
It can be used in applications such as:

- Disinfection systems
- Agricultural spraying
- Smart irrigation
- Industrial automation

The system detects environmental conditions or triggers and activates a pump or spray motor accordingly.

---

## Features

- Automatic spray activation
- Sensor-based triggering
- Adjustable timing logic
- Arduino-based control system
- Proteus simulation included
- HEX file available for deployment

---

## Hardware Components

- Arduino Uno
- Relay Module or MOSFET driver
- Water Pump / Spray Motor
- Sensor (e.g., IR / PIR / Soil moisture depending on design)
- Power Supply

---

## Software

- Arduino IDE (.ino source included)
- Proteus simulation project
- Compiled HEX file included

---

## Project Structure

```
Smart-Spray/
/
/// firmware/
/ /// smart_spray.ino
/
/// simulation/
/ /// proteus-project.pdsprj
/
/// images/
    /// simulation.png
```

---

## Working Principle

1. The sensor monitors environmental conditions.
2. When the trigger condition is met:
   - Arduino activates relay or MOSFET.
   - Pump or spray motor starts.
3. Spray duration is controlled by programmed timing logic.
4. System resets and waits for next trigger.

---

## Future Improvements

- IoT integration for remote monitoring
- Adjustable spray duration via mobile app
- LCD status display
- Water level monitoring sensor
- Battery backup system

---

## License

This project is licensed under the MIT License.

---

## 👥 Authors

Developed collaboratively by:

- Soheil Ahmadi
- Omid Menbari

Open-source project for automation and embedded systems learning.
