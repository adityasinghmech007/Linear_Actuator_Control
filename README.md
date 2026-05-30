# Linear Actuator Testing & Control Firmware

## 📌 Overview

This project is an STM32-based embedded firmware developed for testing and controlling linear actuators in a closed-loop feedback system. The firmware enables real-time actuator testing, motor control, current monitoring, and mechanical resistance/backlash analysis using sensor feedback and PID-based control.

The system is designed for motion-control and mechatronics applications where actuator performance, load behavior, and motion accuracy need to be analyzed in real time.

---

## 🚀 Features

* Closed-loop DC motor control using PID
* Linear actuator motion testing and validation
* Real-time current consumption monitoring
* Mechanical resistance and backlash detection
* PWM-based motor speed and direction control
* ADC + DMA implementation for efficient sensor acquisition
* UART communication for debugging and live monitoring
* Real-time feedback processing using STM32 peripherals
* Modular firmware structure for scalability and testing

---

## 🛠️ Hardware Requirements

To run this firmware, the following hardware is required:

* STM32 Development Board
* INA226 Current & Voltage Sensor
* FT232RL UART Interface IC
* DC Motor Driver
* Linear Actuator Assembly
* External Power Supply

---

## ⚙️ System Functionality

The firmware continuously monitors actuator movement and motor current while controlling motor operation through a PID-based feedback loop.

### Key Functionalities

* Reads analog feedback signals using ADC with DMA
* Controls motor speed using PWM
* Monitors motor current and voltage using INA226
* Sends debugging and telemetry data through UART
* Detects increased resistance/load conditions
* Evaluates backlash and actuator response behavior
* Supports real-time tuning and testing workflows

---

## 🔧 STM32 Peripheral Usage

### ADC + DMA

* Continuous sensor data acquisition
* Efficient CPU utilization
* Real-time analog feedback processing

### PWM

* Motor speed control
* Direction and motion management

### UART

* Serial debugging and telemetry output
* Live monitoring through FT232RL

### Timers & Interrupts

* Periodic control loop execution
* PID update timing and synchronization

---

## 📊 Applications

* Linear actuator testing
* Motion system validation
* Mechanical resistance analysis
* Backlash testing
* Embedded motor control research
* Robotics and automation systems
* Mechatronics prototyping

---

## 💻 Technologies Used

* STM32 MCU
* Embedded C
* STM32 HAL Libraries
* ADC with DMA
* PWM Motor Control
* UART Communication
* PID Control
* INA226 Sensor Interface

---

## 📷 Project Highlights

* Real-time closed-loop actuator control system
* Practical implementation of PID motor control
* Efficient sensor acquisition using DMA
* Embedded testing platform for actuator validation
* Designed for robotics and industrial automation workflows

---

## 🚀 Future Improvements

* Data logging support
* Graphical monitoring interface
* Automated test sequence generation
* Multi-axis actuator testing
* CAN/Ethernet communication support

---

Developed for practical embedded control, actuator characterization, and real-time mechatronics system testing using STM32 microcontrollers.



