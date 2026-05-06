# RTOS Project Portfolio

A comprehensive collection of embedded systems and Real-Time Operating System (RTOS) experiments developed using the STM32F446RE microcontroller, STM32CubeIDE, and FreeRTOS.

This repository demonstrates practical implementation of embedded firmware concepts including GPIO control, timer peripherals, PWM generation, interrupt handling, sensor interfacing, multitasking, task synchronization, inter-task communication, and resource management in real-time systems.

The projects are structured progressively, beginning with fundamental bare-metal embedded programming and advancing toward RTOS-based application development.

---

# Development Environment

## Hardware Platform
- STM32F446RE Nucleo Development Board
- HC-SR04 Ultrasonic Sensor
- Push Buttons
- LEDs
- Breadboard and Interfacing Components

## Software Tools
- STM32CubeIDE
- STM32CubeMX
- FreeRTOS Kernel
- Embedded C Language

---

# Experiment 1: GPIO LED Blinking

## Objective
Configure a GPIO pin as a digital output and implement LED blinking using software delay routines.

## Key Concepts
- GPIO Initialization
- Digital Output Control
- Software-Based Delay Mechanism
- Basic Embedded Firmware Development

## Result
Validated GPIO output functionality through periodic LED blinking.

---

# Experiment 2: Push Button Interfacing

## Objective
Interface a push button as a digital input and toggle an LED state upon detecting a valid button press.

## Key Concepts
- GPIO Input Configuration
- Button Debouncing
- Edge Detection
- State-Based LED Control

## Result
Successfully implemented reliable button-controlled LED toggling.

---

# Experiment 3: HC-SR04 Ultrasonic Sensor Interfacing

## Objective
Interface an HC-SR04 ultrasonic sensor with STM32F446RE and classify measured distances using LED indications.

## Key Concepts
- Ultrasonic Sensor Interfacing
- Timer-Based Pulse Measurement
- Distance Computation
- Real-Time Signal Processing

## Result
Accurately measured object distance and displayed range classifications using LEDs.

---

# Experiment 4: PWM-Based LED Brightness Control

## Objective
Generate a PWM signal using timer peripherals and control LED brightness by varying the duty cycle.

## Key Concepts
- Timer Configuration
- Pulse Width Modulation (PWM)
- Duty Cycle Adjustment
- Hardware Peripheral Control

## Result
Successfully achieved variable LED intensity control using PWM signals.

---

# Experiment 5: Super Loop Embedded Architecture

## Objective
Develop a super loop-based embedded application capable of sequentially executing multiple operations such as LED blinking, button monitoring, and sensor acquisition.

## Key Concepts
- Super Loop Scheduling
- Cooperative Execution Model
- Timing Counters
- Embedded System Workflow Design

## Result
Implemented a structured non-RTOS embedded application with multiple functional modules.

---

# Experiment 6: Basic FreeRTOS Task Implementation

## Objective
Create a basic FreeRTOS project and validate task execution through periodic LED blinking.

## Key Concepts
- FreeRTOS Integration
- Task Creation and Scheduling
- RTOS Delay APIs
- Concurrent Execution Fundamentals

## Result
Successfully created and executed a standalone RTOS task.

---

# Experiment 7: Multi-Tasking with Task Priorities

## Objective
Implement multiple FreeRTOS tasks with different priority levels and analyze scheduling behavior.

## Key Concepts
- Multi-Tasking
- Priority-Based Scheduling
- Context Switching
- RTOS Task Management

## Result
Observed deterministic task execution behavior based on assigned priorities.

---

# Experiment 8: External Interrupt Synchronization using Semaphore

## Objective
Configure an external interrupt for user input and synchronize an RTOS task using task notifications or binary semaphores.

## Key Concepts
- External Interrupt Configuration (EXTI)
- Interrupt Service Routines (ISR)
- Binary Semaphores
- Task Synchronization Mechanisms

## Result
Successfully synchronized task execution with external interrupt events.

---

# Experiment 9: Inter-Task Communication using FreeRTOS Queue

## Objective
Implement queue-based communication between producer and consumer tasks, with UART-based data transmission.

## Key Concepts
- FreeRTOS Queues
- Inter-Task Communication (IPC)
- UART Communication
- Producer-Consumer Architecture

## Result
Successfully exchanged and transmitted task data using queue mechanisms.

---

# Experiment 10: Shared Resource Management using Counting Semaphore

## Objective
Model a limited shared resource using counting semaphores and analyze controlled access among multiple tasks.

## Key Concepts
- Counting Semaphores
- Resource Allocation
- Task Synchronization
- Concurrent Resource Access Management

## Result
Implemented controlled multi-task access to shared system resources.

---

# Repository Structure

```text
RTOS-Project-Portfolio/
│
├── Experiment_01_GPIO_LED/
├── Experiment_02_Button_Interface/
├── Experiment_03_HCSR04/
├── Experiment_04_PWM_Control/
├── Experiment_05_SuperLoop_Architecture/
├── Experiment_06_FreeRTOS_Basic_Task/
├── Experiment_07_Task_Priority_Scheduling/
├── Experiment_08_EXTI_Semaphore_Synchronization/
├── Experiment_09_Queue_UART_Communication/
├── Experiment_10_Counting_Semaphore/
│
├── Docs/
├── Drivers/
├── Core/
└── README.md
