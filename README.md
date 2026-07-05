# Wireless Multimedia Control Panel

An ESP32-based wireless multimedia control panel designed to act as a compact, customizable control deck for media playback, shortcuts, device control, and real-time system feedback. The project combines embedded firmware, wireless communication, tactile inputs, analog controls, OLED display output, and signal filtering to create a responsive hardware interface.

## Overview

This project was built to explore embedded systems, human-machine interfaces, wireless communication, and real-time input processing. The control panel uses an ESP32 microcontroller to read button inputs, process analog controls, update an OLED display, and communicate wirelessly using Bluetooth Low Energy and Wi-Fi.

The goal was to create a reliable and expandable multimedia control device that could be used for functions such as volume control, media playback, shortcut triggering, device status display, and custom command execution.

## Features

* ESP32-based embedded control system
* Bluetooth Low Energy communication
* Wi-Fi connectivity for future network-based control features
* OLED display for menu navigation and system feedback
* Real-time clock module for time-based display and scheduling features
* Tactile push buttons for media and shortcut control
* Analog input controls for smooth adjustment, such as volume or brightness
* Adaptive filtering to reduce noise and smooth analog signal readings
* Modular firmware structure for easier expansion and debugging

## Hardware Used

* ESP32 development board
* OLED display
* RTC module
* Tactile push buttons
* Potentiometers or analog control inputs
* Jumper wires / breadboard or custom wiring
* USB cable for programming and power

## System Architecture

The system is divided into four main sections:

1. **Input Handling**
   Reads tactile button presses and analog control values from the user interface.

2. **Signal Processing**
   Applies adaptive filtering to analog signals to reduce jitter and create smoother control behavior.

3. **Display Interface**
   Updates the OLED screen with status information, selected modes, time, or control feedback.

4. **Wireless Communication**
   Uses BLE and Wi-Fi capabilities of the ESP32 to support wireless control and future expansion.

## Firmware Functionality

The embedded firmware handles:

* GPIO button detection
* Analog-to-digital conversion
* Debouncing for tactile inputs
* Adaptive filtering for analog values
* OLED display updates
* BLE/Wi-Fi communication setup
* Real-time control logic

## Example Use Cases

* Wireless media control deck
* Volume and playback controller
* Custom shortcut keypad
* Smart home or AV system control panel
* Embedded HMI prototype
* ESP32 firmware development platform

## Project Goals

The main goals of this project were to:

* Build a practical embedded user interface
* Gain experience with ESP32 wireless communication
* Improve firmware organization and debugging skills
* Create a smooth analog control experience using filtering
* Integrate multiple peripherals into one embedded system
* Demonstrate hardware-software integration for a real-world control device

## Skills Demonstrated

* Embedded C/C++ programming
* ESP32 firmware development
* GPIO, ADC, I2C, BLE, and Wi-Fi
* OLED display integration
* Real-time input processing
* Analog signal filtering
* Hardware-software integration
* Debugging and validation of embedded systems

## Future Improvements

* Add custom PCB design for a cleaner final build
* Add USB HID support for keyboard/media key commands
* Create a desktop companion app
* Add menu-based configuration on the OLED display
* Add battery power and charging circuit
* Add enclosure design for a finished product
* Expand Wi-Fi support for MQTT, REST API, or smart home control

## Status

Prototype completed. Core firmware functionality includes input handling, wireless communication, display updates, and adaptive analog filtering.

## Author

Kunaal Parikh
Embedded Systems Engineer
GitHub: [k-parikh](https://github.com/k-parikh)
