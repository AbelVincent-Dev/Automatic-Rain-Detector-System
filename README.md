# Automatic Rain Detection System

A home-automation rain detection prototype built with **Arduino** and a **Water sensor module** for real-time weather sensing and automated alert/response triggering.

## Hardware Components
* Arduino Microcontroller (Uno / NodeMCU)
* Water Sensor Module (sensing pad + LM393 comparator board)
* Buzzer / LED / Actuator Trigger Output
* Jumper Wires

## Pin Connections
| Component | Pin | Arduino Pin |
| :--- | :--- | :--- |
| Water Sensor Module | VCC / GND | 5V / GND |
| Water Sensor Module | A0 | A0 |
| Water Sensor Module | D0 | D2 |
| Alert Buzzer / Output | (+) / (-) | D8 / GND |

## Key Features
* **Dual-Mode Detection:** Uses both analog readings (to gauge rain intensity) and digital comparator interrupts for fast response.
* **Calibrated Thresholds:** Tuned sensitivity to prevent false alerts from morning dew or humidity.
