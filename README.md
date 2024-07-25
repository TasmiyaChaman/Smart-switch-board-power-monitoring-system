# Smart Switch Board Power Monitoring Project

## Overview
This project involves designing a PCB that monitors and displays the power consumption from a particular plug point. The PCB integrates a microcontroller STM32 for control and monitoring purposes. Additionally, it includes a controllable switch for managing power to the connected device.

## Features
- **Power Monitoring**: Real-time monitoring of power consumption.
- **Display**: Monitors and display power consumption,power factor, and Capabilit of storing and transmitting data .
- **Controllable Switch**: Plug can enable with timer, it can be programmed for turning on and off at fixed intervals,can be controlled by a switch.
- **Microcontroller**: STM32 microcontroller for processing and control.

## Components
- **STM32 Microcontroller**: Handles data processing and control functions.
- **Current Sensor**: Measures the current flowing through the plug point.
- **Voltage Sensor**: Measures the current flowing through the plug point.
- **Display Module**: Displays real-time power consumption data.
- **Switching Relay**: Controls the power supply to the connected device.
- **Power Supply**: Provides necessary power to the PCB and connected devices.


<img src="https://github.com/TasmiyaChaman/Smart-switch-board-power-monitoring-system/blob/main/PCB%20Schematics.png" alt="Schematics" width="900" height="700">
<p>Figure 1: Schematics of the PCB design.</p>



<img src="https://github.com/TasmiyaChaman/Smart-switch-board-power-monitoring-system/blob/main/PCB%20Routing.png" alt="Schematics" width="800" height="600">
<p>Figure  2: PCB Routing design.</p>
<br> <!-- Line break for spacing -->

<img src="https://github.com/TasmiyaChaman/Smart-switch-board-power-monitoring-system/blob/main/Layout%20design.png" alt="Schematics" width="800" height="600">
<p>Figure 3: PCB layout design.</p>

## Installation and Setup
1. **Hardware Setup**:
   - Connect the PCB to the power source and the plug point to be monitored.
   - Ensure all components are securely connected as per the schematic.

2. **Software Setup**:
   - Program the STM32 microcontroller with the provided firmware.
   - Configure any necessary settings for the display and current sensor.
![Ideal Switch Board]()
*Figure 2: Switch Board.*


## Usage
1. **Power On**: Activate the device by supplying power.
2. **Monitoring**: The display will show real-time power consumption.
3. **Control**: Use the switch functionality to remotely control the connected device.
4. **Data Logging**: Optionally, implement data logging features to track power consumption over time.
