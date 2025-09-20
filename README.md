# Thrust Stand PCB Design

This repository contains the source code and documentation for the **Thrust Stand PCB**,  
where an **ESP32 microcontroller** interfaces with multiple sensors to measure **motor thrust, RPM, current, voltage, and temperature**.  
The system provides **real-time monitoring, on-screen display, and SD card data logging** for propulsion testing.

## 🚀 Features
- **Thrust Measurement**: Uses a load cell with HX711 amplifier to measure motor thrust accurately.  
- **Temperature Monitoring**: MAX6675 thermocouple interface tracks motor/ESC temperature.  
- **RPM Detection**: Optical RPM sensor (TCRT5000) monitors motor shaft speed.  
- **Current & Voltage Sensing**: ACS758LCB current sensor and voltage divider circuit measure electrical performance.  
- **ESC Control Interface**: Generates PWM signals to control motor speed via ESC.  
- **Data Logging**: Records thrust, RPM, voltage, current, and temperature to SD card for analysis.  
- **OLED Display**: Real-time display of test parameters for quick observation.  
- **Stable Power Regulation**: LM2596 buck converter regulates battery input to 3.3V for ESP32 and sensors.  

## 🧰 Components Used
- **ESP32 Dev Board**  
- **HX711 + Load Cell** (for thrust measurement)  
- **MAX6675 Thermocouple Interface** (for temperature sensing)  
- **TCRT5000 RPM Sensor**  
- **ACS758LCB-100U Current Sensor**  
- **Voltage Divider Circuit** (for battery voltage measurement)  
- **Electronic Speed Controller (ESC) + Motor**  
- **OLED Display (SSD1306)**  
- **SD Card Module** (for data logging)  
- **LM2596 Buck Converter** (for power regulation)  
- **Battery Pack**, **Connectors**, and **Wiring**  

## 📁 Project Structure
- **Schematic**: Circuit design showing ESP32, sensors, ESC, power supply, and peripherals.  
- **Block Diagram**: High-level representation of system flow (sensors → ESP32 → display/logging).  
- **PCB Layout**: Board design for compact integration of all components.  
- **3D View**: Rendered visualization of the PCB.  

---
