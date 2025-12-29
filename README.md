# Home Innovation System

An IoT-based home safety and security system that detects gas leakage, smoke/fire, and human motion, and sends emergency alerts using GSM communication.

## Objective
Design and implement a smart home security system capable of detecting theft, fire, and gas leakage and notifying the owner through SMS alerts.

## Features
- Gas leakage detection using MQ-6 sensor
- Smoke/fire detection using MQ-2 sensor
- Motion detection using PIR sensor
- GSM-based SMS alerts for emergencies
- Buzzer/actuator activation for immediate warning

## Hardware Components
| Component | Model |
|-----------|--------|
| Microcontroller | Arduino UNO |
| Gas Sensor | MQ-6 |
| Smoke Sensor | MQ-2 |
| Motion Sensor | PIR |
| GSM Module | SIM900A |
| Buzzer | Piezoelectric |
| Power Supply | 12V, 2A |

## System Working
1. Sensors continuously monitor gas, smoke, and motion.
2. Arduino processes sensor data and checks against threshold values.
3. If danger is detected, the GSM module sends an SMS alert to the owner.
4. The buzzer is activated to provide local warning.

## Applications
- Home security systems
- Fire and gas safety in offices, labs, and industries
- Intrusion detection in restricted areas

## Documentation
Detailed report and block diagram are available in the `/docs` and `/images` folders.

## Preview
<img width="772" height="500" alt="image" src="https://github.com/user-attachments/assets/32627a3a-0176-4d3b-afd5-32d06687f687" />


## Author
Kasak — Electrical Engineering student
