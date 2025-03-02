# RFID System for Secure Access Control

## Overview
This project implements a **Radio-Frequency Identification (RFID) system** using an **STM32F446RE microcontroller**. The system reads RFID tags to control access, ensuring secure and efficient identification.

## Features
✅ **RFID Tag Reading** – Detects and reads unique tag IDs.  
✅ **Access Control** – Grants or denies access based on predefined authorized tag IDs.  
✅ **Scalability** – Easily add or remove authorized tags through firmware updates.  
✅ **Secure Communication** – Uses UART/SPI/I2C to interface with the RFID reader.  
✅ **Low Power Consumption** – Optimized for embedded applications.  

---

## Hardware Components
- **Microcontroller:** STM32F446RE
- **RFID Reader Module:** Compatible with 13.56 MHz RFID tags
- **Power Supply:** 3.3V/5V DC
- **Communication Interface:** UART/SPI/I2C (based on module specs)
- **Indicators:** LED/Buzzer for access status

---

## Software Components
- **Development Environment:** STM32CubeIDE
- **Programming Language:** Embedded C
- **Peripheral Libraries:** STM32 HAL (Hardware Abstraction Layer)
- **Debugger:** ST-Link v2 for debugging & programming

---

Open the Project in STM32CubeIDE
Launch STM32CubeIDE.
Navigate to File > Open Projects from File System....
Select the cloned repository folder.
   Build & Flash the Firmware
Compile the project to generate the firmware binary.
Connect the STM32F446RE board via USB.
Use ST-Link v2 to flash the firmware onto the microcontroller.
   Connect the RFID Reader
Interface the RFID reader module to the STM32F446RE board.
Ensure correct wiring (TX/RX pins for UART).
    Test the System
Present an RFID tag to the reader.
Check if access is granted or denied based on stored IDs.
