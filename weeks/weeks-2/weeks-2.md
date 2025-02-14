# Week 2 Study Plan for STM32/Nucleo Projects

## Overview
This detailed 7-day study plan for Week 2 expands on Week 1, focusing on STM32 peripherals with hands-on programming exercises.

| **Day** | **Topics to Cover** | **Detailed Description** |
|--------|---------------------|-------------------------|
| **Day 1** | 📡 **UART Communication Basics** | Learn UART for serial communication, configure using *STM32CubeMX*, and send/receive data via Serial Monitor. |
| **Day 2** | ⚙️ **ADC (Analog-to-Digital Conversion)** | Understand ADC operation, configure with *STM32CubeMX*, and read analog inputs (e.g., potentiometer) via UART. |
| **Day 3** | 💡 **Interrupts and NVIC** | Study NVIC for managing interrupts, set up external interrupts, and toggle LEDs using a push-button. |
| **Day 4** | 🧵 **PWM for Motor Control** | Configure PWM signals with variable duty cycles to control motor speed and create smooth transitions. |
| **Day 5** | 🌐 **SPI Communication** | Explore SPI protocol, configure master-slave communication, and exchange data with sensors via SPI. |
| **Day 6** | 🗃️ **I2C Communication** | Learn I2C protocol, configure using *STM32CubeMX*, and interface with sensors like a temperature module. |
| **Day 7** | 📝 **Review, Practice, and Mini Project** | Revise the week’s concepts and create a project displaying temperature data from I2C via UART. |

## Detailed Daily Descriptions
### 📡 Day 1: UART Communication Basics
- Understand the importance of serial communication in embedded systems.
- Study the USART section from the STM32G474xx datasheet.
- Configure UART using *STM32CubeMX* and write a program to send and receive data using a serial monitor.

### ⚙️ Day 2: ADC (Analog-to-Digital Conversion)
- Learn how an ADC converts analog signals to digital values.
- Configure an ADC channel to read a potentiometer value.
- Display the ADC readings via UART.

### 💡 Day 3: Interrupts and NVIC
- Study how the NVIC handles interrupts.
- Configure an external interrupt (e.g., from a push button) to toggle an LED.
- Understand interrupt priority levels.

### 🧵 Day 4: PWM for Motor Control
- Revisit PWM concepts from Week 1.
- Configure a timer for PWM output.
- Write code to control a motor's speed using varying duty cycles.

### 🌐 Day 5: SPI Communication
- Understand the SPI communication protocol.
- Configure STM32 as an SPI master.
- Communicate with an SPI-based sensor or module.

### 🗃️ Day 6: I2C Communication
- Study I2C communication and its uses.
- Configure STM32 as an I2C master.
- Interface with a temperature sensor and read data via I2C.

### 📝 Day 7: Review, Practice, and Mini Project
- Revise all the topics covered from Day 1 to Day 6.
- Practice coding with mini-exercises for each peripheral.
- Build a mini-project: Read temperature via I2C and display it through UART.

---
### ✅ Keep Learning, Keep Building! 🚀
