# PLC-Based Smart Elevator System

## Overview
This project implements a **smart elevator system** using a **Programmable Logic Controller (PLC)**. The system automates the movement of the elevator, detects its position using a sensor, and responds to user input to select floors.

## Project Structure
- **Main Logic**: Ladder logic for the elevator control program.
- **Hardware Design**: Wiring diagrams for PLC, sensors, and actuators.
- **Simulation**: A basic simulation environment for testing the system.

## Technologies Used
- **PLC**: Siemens PLC (e.g., Siemens S7-1200)
- **Programming**: Ladder Logic (Siemens TIA Portal)
- **Components**:
  - Sensor for floor detection
  - Actuators for elevator movement
  - Buttons for floor selection
  - Emergency stop system

## Features
- **Automated Floor Selection**: Elevator moves based on user input.
- **Position Detection**: Sensor detects current floor.
- **Emergency Stop**: Immediate stop in case of malfunction or emergency.
- **LED Display**: Displays the current floor number.

## Installation & Setup

### Prerequisites
- Siemens TIA Portal (or any Siemens-compatible PLC programming software)
- Siemens PLC (e.g., S7-1200)
- Sensor and Actuators as per the system design

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/PLC-Smart-Elevator-System.git
