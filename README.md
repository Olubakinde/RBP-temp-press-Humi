# Temperature Logger with Sense HAT

## Description

This Python script reads temperature, humidity, and pressure data from the Sense HAT attached to a Raspberry Pi and displays it on the Sense HAT LED matrix. It also logs the data to a file (`weather.txt`) every 30 seconds. The temperature is converted to Fahrenheit for display and logging purposes.

## Requirements

- Raspberry Pi with Sense HAT
- Python 3
- Sense HAT library
- Run the Script - run python3 temp.py

## Installation

1. **Install the Sense HAT library:**
   ```bash
   sudo apt-get update
   sudo apt-get install sense-hat
