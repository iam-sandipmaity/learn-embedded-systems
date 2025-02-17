# 📘 Embedded Systems Learning Roadmap (Beginner to Pro)

**📅 Duration:** 14 Weeks 

**✍️ Author:** [Sandip Maity](https://github.com/iam-sandipmaity) | [LinkedIn](https://www.linkedin.com/in/iam-sandipmaity/) | [X (Twitter)](https://x.com/iam_sandipmaity) | [Instagram](https://www.instagram.com/iam_sandipmaity/)

**🎯 Focus Areas:** STM32, IoT, RTOS, Embedded C, Communication Protocols, Secure Coding

## 🛤️ Overview
Welcome to the Embedded Systems Learning Repository! 🚀 This comprehensive project serves as your gateway to mastering embedded systems development, offering carefully curated resources, practical code examples, and hands-on projects. Our primary focus is on industry-standard STM32 and Arduino microcontrollers, providing you with real-world development experience.

This meticulously structured repository guides you through the fascinating world of embedded systems, covering everything from STM32 microcontrollers and RTOS concepts to IoT integration and secure coding practices. The 14-week program is thoughtfully designed to build your expertise progressively - starting from fundamental concepts and culminating in an advanced capstone project that showcases your mastery of embedded systems development.

# Table of Contents
- [Folder Structure](#-folder-structure)
- [Full Roadmap Summary](#-full-roadmap-summary)
- [Prerequisites Skills](#-prerequisites-skills)
- [Tools & Technologies](#-tools-technologies)
- [How to Use This Repository](#-how-to-use-this-repository)
- [Contributing](#-contributing) 
- [Learning Resources](#-learning-resources)
- [Projects And Examples](#-projects-and-examples)
- [FAQ](#-faq)
- [Final Note](#-final-note)
- [Stay Connected](#-stay-connected)


---
## 📂 Folder Structure
| **Folder**         | **Contents**                                        |
|-------------------|--------------------------------------------------|
| `week-1` to `week-14` | Weekly study plans with topics, projects, and resources |
| `projects/`        | Complete projects with source code and documentation |
| `resources/`       | Helpful PDFs, datasheets, cheat sheets, and tutorials |
| `final-project/`   | Capstone IoT project with code and documentation |

---
## 📅 Full Roadmap Summary
| **Week** | **Topics Covered**                | **Key Learning Areas**                  | **Tools & Technologies**         |
|---------|------------------------------------|-----------------------------------------|----------------------------------|
| [1](./weeks/weeks-01/weeks-1.md)       | Introduction to STM32 & GPIO       | STM32CubeIDE, GPIO configurations       | STM32CubeIDE, HAL APIs           |
| [2](./weeks/weeks-02/weeks-2.md)       | GPIO Projects & External Interrupts| Button, LED projects, EXTI interrupts   | STM32CubeIDE, HAL APIs           |
| [3](./weeks/weeks-03/weeks-3.md)       | Timers & PWM                       | STM32 timers, PWM for LED control       | STM32CubeIDE, HAL APIs           |
| [4](./weeks/weeks-04/weeks-4.md)       | Analog to Digital Conversion (ADC) | ADC for sensor readings, potentiometer  | STM32CubeIDE, HAL APIs           |
| [5](./weeks/weeks-05/weeks-5.md)       | UART Communication                 | Serial communication, debugging via UART| STM32CubeIDE, UART Monitor       |
| [6](./weeks/weeks-06/weeks-6.md)       | SPI & I2C Protocols                | Sensor interfacing (e.g., OLED display) | STM32CubeIDE, Logic Analyzer     |
| [7](./weeks/weeks-07/weeks-7.md)       | Introduction to RTOS               | FreeRTOS basics, tasks, queues          | STM32CubeIDE, FreeRTOS           |
| [8](./weeks/weeks-08/weeks-8.md)       | Advanced RTOS Concepts             | Mutexes, semaphores, and timers         | STM32CubeIDE, FreeRTOS           |
| [9](./weeks/weeks-09/weeks-9.md)       | DMA & Interrupt Handling           | DMA transfers, interrupt priorities     | STM32CubeIDE, HAL APIs           |
| [10](./weeks/weeks-10/weeks-10.md)      | Low Power Modes                    | Sleep, stop modes for energy efficiency | STM32CubeIDE, HAL APIs           |
| [11](./weeks/weeks-11/weeks-11.md)      | Debugging Techniques               | SWV, breakpoints, watchdog timers       | STM32CubeIDE, ST-Link Utility    |
| [12](./weeks/weeks-12/weeks-12.md)      | Secure Coding Practices            | CRC checks, secure boot implementation  | STM32CubeIDE, TrustZone Docs     |
| [13](./weeks/weeks-13/weeks-13.md)      | Wireless Communication (IoT)       | ESP8266 (Wi-Fi), MQTT, LoRa, BLE        | STM32CubeIDE, Thingspeak API     |
| [14](./weeks/weeks-14/weeks-14.md)      | Capstone Project: IoT System       | Integrating all learned concepts        | STM32CubeIDE, FreeRTOS, LoRa     |

---
## 📚 Prerequisites Skills

### Hardware Skills


| **Prerequisites**                                   | **Level**         | **Description**                              |   
|-----------------------------------------------------|-------------------|----------------------------------------------|
| Microcontroller Fundamentals                        | Beginner          | Understanding of microcontroller architecture|
| Familiarity with STM32 and Arduino microcontrollers | Beginner          | Industry-standard microcontroller family     |
| Understanding of basic sensors and actuators        | Beginner          | Helps in understanding circuit connections   |
| Basic electronics knowledge                         | Beginner          | Helps in understanding circuit connections   |


### If you are a beginner, you can start with the following topics:
- [Microcontroller Fundamentals](https://www.electronicsforu.com/technology-trends/learn-electronics/microcontroller-basics)
- [STM32 Fundamentals](https://stm32-base.org/guides/getting-started.html)
- [Basic Electronics](https://www.electronics-tutorials.ws/)
- [Basic Sensors and Actuators](https://ipcsautomation.com/blog-post/basic-concepts-of-sensors-and-actuators/)

### Software Skills

| **Prerequisites**                                   | **Level**         | **Description**                              |   
|-----------------------------------------------------|-------------------|----------------------------------------------|
| C Programming                                       | Beginner          | Essential for embedded systems development   |
| STM32 CUBE IDE                                      | Beginner          | Industry-standard microcontroller family     |
| FreeRTOS                                            | Beginner          | Real-time operating system                   |
| Arduino IDE                                         | Beginner          | Helps in understanding circuit connections   |
| VSCode  Or Cursor IDE                               | Beginner          | Helps in understanding circuit connections   |

### If you are a beginner, you can start with the following topics:
- [C Programming](https://devdocs.io/c/)
- [STM32 Fundamentals](https://controllerstech.com/stm32/)
- [FreeRTOS](https://www.freertos.org/)
- [Arduino IDE](https://www.arduino.cc/en/software)
- [VSCode](https://code.visualstudio.com/)
- [Cursor IDE](https://www.cursor.com/)


### By the way, you can use any IDE to code, but I recommend you to use STM32 CUBE IDE and Arduino IDE.

And If you are still confused about prerequisites, you can ask me in the [Discussions](https://github.com/iam-sandipmaity/learn-embedded-systems/discussions) section. Also, you can  start your journey from the [Week 1](./weeks/weeks-01/weeks-1.md) folder without any hesitation and any prerequisites because I will cover all the prerequisites in this roadmap. 


---
## 🛠️ Tools & Technologies
| **Category**        | **Examples**                          |
|---------------------|---------------------------------------|
| IDE & Compilers     | STM32CubeIDE, VSCode, PlatformIO      |
| Programming Language| Embedded C, C++                       |
| Microcontrollers    | STM32F1, Nucleo-G474                  |
| IoT Modules         | ESP8266 (Wi-Fi), LoRa, HC-05 (BLE)    |
| Communication Tools | UART Monitor, Logic Analyzer          |
| Frameworks          | FreeRTOS                              |
| Cloud Platforms     | Thingspeak API, MQTT                  |

---
## 📝 How to Use This Repository
1. **Fork the Repository:**
   - Click the "Fork" button at the top right of the repository page.
   - This creates a copy of the repository under your GitHub account.

2. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/learn-embedded-systems.git
   ```
3. **Navigate to Weekly Folders:** Each week contains a README with topics and tasks.
4. **Practice Projects:** Follow tasks, complete projects, and document your progress.
5. **Push Your Progress:** Commit your projects to your repository regularly.

---

## 🙌 Contributing
- [How To Contribute in this Repo?](https://github.com/iam-sandipmaity/learn-embedded-systems/blob/main/CONTRIBUTING.md) 
- **Issues:** Raise issues for questions or suggestions.
- **Pull Requests:** Contribute new projects or corrections.
- **Resources:** Add useful learning materials.

--- 
## 📚 Learning Resources

### IDEs & Development Tools
- [STM32 CUBE IDE](https://www.st.com/en/development-tools/stm32cubeide.html)
- [Arduino IDE](https://www.arduino.cc/en/software)
- [VSCode](https://code.visualstudio.com/)
- [Cursor IDE](https://www.cursor.com/)

### Official Documentation
- [FreeRTOS](https://www.freertos.org/)
- [STM32 Official Documentation](https://www.st.com/en/embedded-software/stm32-embedded-software/documentation.html)
- [Arduino Official Documentation](https://www.arduino.cc/en/software)
- [VSCode Official Documentation](https://code.visualstudio.com/)
- [Cursor IDE Official Documentation](https://www.cursor.com/)
- [FreeRTOS Official Documentation](https://www.freertos.org/)

### Learning Platforms
- [YouTube](https://www.youtube.com/)
- [Udemy](https://www.udemy.com/)
- [Coursera](https://www.coursera.org/)
- [edX](https://www.edx.org/)
- [Coursera](https://www.coursera.org/)

### Books
- [Mastering Embedded Systems Development](https://www.amazon.in/Mastering-Embedded-System-Scratch-Second-ebook/dp/B0CHR33RNV)
- [The Definitive Guide to the ARM Cortex-M3](https://www.amazon.in/Definitive-Guide-Cortex-M3-Embedded-Technology/dp/0750685344)
- [Embedded Systems: Introduction to ARM Cortex-M Microcontrollers](https://www.amazon.in/Embedded-Systems-Introduction-Cortex-Microcontrollers/dp/1477508996)
- [Mastering STM32](https://www.amazon.in/Mastering-STM32-Beginners-Guide-Programming-ebook/dp/B0CFHZHNRV)

---
## Projects And Examples 
- **GPIO Basics**: LED Blinking, Push Button Input
- **ADC/DAC**: Reading analog sensors, generating waveforms
- **Communication Protocols**: UART, SPI, I2C, CAN
- **Timers and PWM**: Generating PWM signals for motor control
- **RTOS Applications**: FreeRTOS implementation on STM32
- **IoT Projects**: Sensor data collection and cloud communication

---
##  ❓ FAQ

### Q: Which STM32 board should I start with?

**A:** The STM32F103 (Blue Pill) is an affordable and beginner-friendly choice.

### Q: How can I debug my code?

**A:** Use STM32CubeIDE's built-in debugger or VSCode with Cortex-Debug.

### Q: Why does my board not respond after flashing?

**A:** Check the BOOT0 pin configuration and reflash the firmware.

---
## 🌟 Final Note
This roadmap is designed to help you master embedded systems and build a solid portfolio of projects. By completing the weekly tasks and capstone project, you’ll be well-prepared for embedded systems roles and real-world applications. Feel free to ask questions and contribute to the repository.

---
## 📧 Stay Connected

- 🌐 **GitHub:** [Sandip Maity](https://github.com/iam-sandipmaity)
- 🔗 **LinkedIn:** [Sandip Maity](https://www.linkedin.com/in/iam-sandipmaity/)
- 🐦 **X (Twitter):** [Sandip Maity](https://x.com/iam_sandipmaity)

Happy Learning! 🚀😊
