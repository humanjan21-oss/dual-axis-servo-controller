# Dual-Axis Servo Controller

A dual-axis positioning controller built around the PIC18F26K80, using continuous-rotation servos, quadrature encoder feedback, and RS485 communication.

## Why this project exists

This project started as a practical way for my son and me to explore electronics, mechanics, and programming together.

The aim is to build a reusable controller while learning about motion control, position feedback, and communication between devices. Possible applications include robotic arms, steering mechanisms, and other experimental motion projects.

## Main hardware

- PIC18F26K80 microcontroller
- Two modified MG996R continuous-rotation servos
- Two quadrature encoders for position feedback
- MAX485E RS485 interface
- ACS712 current sensing
- External 12 V to 6 V power supply stage

## Current status

The design is under development. Hardware testing and performance validation are pending.

Files and documentation will be added as the project progresses. Published designs may change following testing.

## Planned repository contents

- Firmware source code
- Schematics and PCB design files
- Mechanical arrangement details
- Setup instructions and test results

## Intended operation

A master device sends position targets over RS485. The controller uses encoder feedback to move each axis towards its target and report its status.

Standalone, PC, and wireless control options are areas for future development.
