# Smart Door Locking System using STM32F446RE + FreeRTOS

## Overview

This project demonstrates a **Smart Door Locking System** using the **STM32F446RE Nucleo Board** and **FreeRTOS**.
The system simulates door lock monitoring using multitasking and UART communication.

The project showcases important RTOS concepts such as:

* Multitasking
* Event Flags
* UART Communication
* Interrupt Handling
* Task Scheduling

---

# Features

* FreeRTOS-based multitasking
* UART serial communication using USART2
* Door lock status monitoring
* Event-driven task execution
* Tera Term serial output display
* Beginner-friendly STM32 RTOS project

---

# Hardware Requirements

| Component                 | Quantity    |
| ------------------------- | ----------- |
| STM32F446RE Nucleo Board  | 1           |
| HC-SR04 Ultrasonic Sensor | 1           |
| USB Cable                 | 1           |
| Jumper Wires              | As required |

---

# Software Requirements

* STM32CubeIDE
* STM32CubeMX
* Tera Term / PuTTY
* FreeRTOS

---

# Pin Configuration

| STM32 Pin | Function     |
| --------- | ------------ |
| PA1       | HC-SR04 TRIG |
| PB0       | HC-SR04 ECHO |
| PA2       | USART2_TX    |
| PA3       | USART2_RX    |

---

# USART2 Configuration

| Parameter             | Value   |
| --------------------- | ------- |
| Baud Rate             | 115200  |
| Word Length           | 8 Bits  |
| Stop Bits             | 1       |
| Parity                | None    |
| Hardware Flow Control | Disable |

---

# FreeRTOS Tasks

## Sensor Task

* Simulates door sensor monitoring
* Sends sensor status through UART

## Parking/Door Task

* Simulates door lock state
* Alternates between:

  * Door Locked
  * Door Unlocked

---

# RTOS Concepts Used

| RTOS Feature | Description             |
| ------------ | ----------------------- |
| Tasks        | Parallel execution      |
| Event Flags  | Inter-task signaling    |
| Delays       | Task scheduling         |
| Interrupts   | External event handling |

---

# Serial Output Example

```text
Checking Door Sensor...
Door Locked

Checking Door Sensor...
Door Unlocked
```

---

# How to Run

## 1. Open Project

Import project into STM32CubeIDE.

---

## 2. Build Project

```bash
Ctrl + B
```

---

## 3. Flash STM32

Click:

```text
Run ▶
```

---

## 4. Open Tera Term

Select:

```text
STLink Virtual COM Port
```

Set:

```text
115200 8N1
```

---

# Project Structure

```text
Core/
 ├── Inc/
 ├── Src/
 │    ├── main.c
 │    ├── stm32f4xx_it.c
 │    └── freertos.c
```

---

# Future Improvements

* Real HC-SR04 distance measurement
* Password-based access
* RFID authentication
* IoT monitoring using ESP8266
* Servo motor-based door control
* OLED/LCD display integration

---

# Applications

* Smart Home Systems
* Office Security
* Electronic Door Locks
* Embedded RTOS Learning
* Access Control Systems

---

# Author

Bhavishay Girdhar

---

# License

This project is for educational and learning purposes.
