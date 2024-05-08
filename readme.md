# Command-Based Serial Communication between ESP8266 and Python code

This repository contains code for establishing a command-based serial communication system between an ESP8266 microcontroller and a Python script. The system includes functionalities such as blinking the LED, customizing delay, turning the LED ON/OFF, and halting operations.

## Features

- Default state: Blink LED every second.
- Commands:
  - `bxxxx`: Change the default delay to `xxxx` milliseconds.
  - `oxxxx`: Turn the LED ON for `xxxx` milliseconds.
  - `fxxxx`: Turn the LED OFF for `xxxx` milliseconds.
  - `hxxxx`: Halt operations.

## Requirements

- ESP8266 microcontroller.
- Python 3 environment with `pyserial` library installed.

## Usage

1. Upload the ESP8266 code to your ESP8266 microcontroller.
2. Run the Python script on your computer.
3. Follow the command format mentioned above to control the LED behavior.


If you find this project useful, consider buying me a cup of dark coffee! ☕️
