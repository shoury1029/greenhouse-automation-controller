# Greenhouse Automation Controller System

**PIC18F45K22 | Embedded C | ADC | UART | Timer0 | Stepper Motor**

## Overview
Full greenhouse automation system built on PIC18F45K22 with 
fully autonomous environmental regulation across temperature, 
humidity, and CO2 parameters.

## Features
- Multi-sensor ADC fusion across 3 channels with 10-sample 
  circular buffer and rolling average for noise-resilient readings
- Automated actuator control: Heater, Cooler, Fan, Lighting, 
  and Speaker driven by configurable upper/lower thresholds
- Stepper motor vent driver with bidirectional step-pattern 
  control and position tracking via Timer0-based 1-second 
  interrupt tick
- Dual UART serial communication protocol with XOR checksum 
  validation for reliable multi-node data exchange
- Push-button UI with mode switching, channel selection, and 
  real-time limit adjustment transmitted over UART

## Hardware
- PIC18F45K22 microcontroller
- Temperature, Humidity, CO2 sensors
- Stepper motor for vent control
- Heater, Cooler, Fan, Lighting actuators

## Built With
- Embedded C
- MPLAB X IDE
- Timer0 interrupt architecture
- Dual UART communication
