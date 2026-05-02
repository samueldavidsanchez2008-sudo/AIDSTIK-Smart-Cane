# AIDSTIK - Smart Assistive Technology 🦯
**Ultrasonic Assistance System for Autonomous Mobility**  
*Developed by Samuel | Electronics Engineering Student | IEEE Member*

## 🎯 Overview
AIDSTIK is an intelligent assistive device designed to enhance the autonomy and safety of individuals with visual impairments. The system utilizes proximity sensors and multisensory feedback to detect obstacles in real-time. It applies advanced electronic design principles to ensure hardware reliability and performance.

## 🛠️ Technical Specifications (Hardware Engineering)
The design has been validated under high-quality academic standards, focusing on component protection and power efficiency:

*   **Processing Unit**: ESP32 (WROOM-32) featuring dual-core connectivity.
*   **Power Management (Actuators)**:
    *   **Architecture**: Low-Side Switching utilizing logic-level MOSFETs.
    *   **Active Safety**: 10kΩ pull-down resistors on the Gate to prevent erratic activations during MCU startup.
    *   **Inductive Protection**: Integrated Flyback diodes for suppressing voltage spikes (Back EMF) from the buzzer and motors.
*   **Signal Integrity and Protection**:
    *   **Voltage Dividers**: Implementation of resistive networks (1kΩ/2kΩ) on the ECHO pin to adapt 5V signals to the ESP32's 3.3V tolerant levels.
    *   **Battery Monitoring**: Precision voltage divider (20kΩ/10kΩ) for tracking state-of-charge via ADC (BATT_SENSE).

## 📂 Repository Structure
*   **`/hardware`**: Detailed KiCad schematics, libraries, and PCB design files.
*   **`/firmware`**: Optimized source code for the ESP32 focused on low power consumption.
*   **`/docs`**: Flowcharts, technical calculations, and supporting documentation.
*   **`/3D_Models`**: Mechanical design files for the ergonomic enclosure.

## 🚀 Professional Goals
This project serves as a cornerstone of my technical portfolio, oriented toward **Embedded Systems** and **Robotics**. My long-term objective is to apply these engineering fundamentals to help **My community**.

---
*Designed with technical precision and a passion for innovation.*