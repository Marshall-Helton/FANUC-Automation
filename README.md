# Automated Conveyor Sorting System

## Overview

Developed an automated industrial sorting system that classifies and palletizes metal and plastic components using PLC control logic, industrial sensors, and a FANUC 6-axis robotic arm.

The project was completed as part of a multi-team industrial automation effort involving mechanical design, electrical controls, and robotics integration.

---

## System Architecture

1. Mixed metal and plastic parts travel along a conveyor belt.
2. A custom-designed funnel aligns all parts into a single detection zone.
3. A proximity sensor detects incoming parts.
4. An inductive sensor determines whether the part is metallic.
5. The PLC processes sensor inputs and triggers the appropriate robot routine.
6. The FANUC robotic arm sorts the part into the correct pallet location.
7. The robot changes grippers and passes completed pallets to downstream processes.

---

## My Contributions

### PLC Programming

- Developed RSLogix ladder logic for system operation
- Implemented emergency stop functionality
- Programmed machine state and status indicator controls
- Created sensor-driven event logic for robotic task selection

### Mechanical Design

- Designed a custom funnel component in Autodesk Inventor.
- Attatched to the converyor belt, it optimizes part alignment to improve sensor reliability

### System Integration

- Integrated proximity and inductive sensor inputs with PLC logic
- Assisted with PLC-to-FANUC communication and signal coordination
- Participated in system-level testing and troubleshooting

---

## Technologies Used

| Category | Technology |
|-----------|------------|
| PLC Programming | RSLogix |
| Robotics | FANUC 6-Axis Robot |
| CAD | Autodesk Inventor |
| Sensors | Proximity Sensor, Inductive Sensor |
| Automation | Conveyor Control Systems |

---

## Engineering Concepts

- Industrial Automation
- PLC Programming
- Event-Driven Control Systems
- Sensor Integration
- Robotics Integration
- Hardware-Software Integration
- System Testing and Validation
- Safety Controls and Emergency Stop Logic

---

## Demonstration

Click the image below to watch the system in operation.

[![Automated Conveyor Sorting System Demo](<img width="1372" height="774" alt="image" src="https://github.com/user-attachments/assets/b205286e-ec6f-462a-8209-aa64070d6f21" />
)](https://youtu.be/8ro87KnF2Fk)

---

## Project Notes

This project was completed in a collaborative environment with Robotics Technicians.

While the original PLC codeare no longer available, this repository documents the system architecture, engineering approach, and project outcomes through written documentation and a video demonstration.

The project provided hands-on experience with:

- Industrial automation systems
- PLC programming and control logic
- Sensor-based classification systems
- Robotics integration
- Cross-disciplinary engineering collaboration
- Real-time event-driven control systems
