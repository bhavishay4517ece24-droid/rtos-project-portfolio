# RTOS Project Portfolio

This repository contains a collection of embedded systems and FreeRTOS experiments implemented on the STM32F446RE development board using STM32CubeIDE and Embedded C.

The experiments focus on GPIO programming, timers, interrupts, sensor interfacing, PWM generation, task scheduling, inter-task communication, semaphores, and UART communication using FreeRTOS.

---

# Hardware and Software Used

## Hardware
- STM32F446RE Nucleo Board
- HC-SR04 Ultrasonic Sensor
- Push Button
- LEDs
- Breadboard and Jumper Wires

## Software
- STM32CubeIDE
- STM32CubeMX
- FreeRTOS
- Embedded C

---

# Experiment 1: LED Blinking using GPIO Output

## Objective
To configure a GPIO pin of STM32F446RE as digital output and verify LED blinking operation using software delay routines.

## Concepts Covered
- GPIO Configuration
- Digital Output
- Software Delay
- Embedded C Programming

## Outcome
Successfully controlled onboard LED blinking using GPIO output mode.

---

# Experiment 2: Push Button Interfacing

## Objective
To interface a push button as digital input and demonstrate LED control by toggling its state on each valid button press.

## Concepts Covered
- GPIO Input Configuration
- Button Debouncing
- State Toggling
- Digital Input Handling

## Outcome
LED state changed correctly on each button press.

---

# Experiment 3: HC-SR04 Ultrasonic Sensor Interfacing

## Objective
To interface an HC-SR04 ultrasonic sensor with STM32F446RE and classify distance ranges using visual indication through LEDs.

## Concepts Covered
- Sensor Interfacing
- Timer Measurement
- Distance Calculation
- GPIO Output Indication

## Outcome
Measured object distance successfully and indicated distance ranges using LEDs.

---

# Experiment 4: PWM Signal Generation

## Objective
To generate a PWM signal using a timer on STM32F446RE and control the brightness of an onboard LED by varying the duty cycle.

## Concepts Covered
- PWM Generation
- Timer Configuration
- Duty Cycle Control
- LED Brightness Control

## Outcome
Successfully varied LED brightness using PWM signals.

---

# Experiment 5: Super Loop Based Embedded Program

## Objective
To implement a super loop-based embedded program that sequentially performs LED blinking, button status reading, and sensor data acquisition using simple timing counters.

## Concepts Covered
- Super Loop Architecture
- Cooperative Scheduling
- Timing Counters
- Embedded System Design

## Outcome
Implemented multiple functionalities in a sequential embedded loop structure.

---

# Experiment 6: Basic FreeRTOS LED Task

## Objective
To develop a basic FreeRTOS-based project on STM32F446RE in STM32CubeIDE and validate LED blinking using a single RTOS task.

## Concepts Covered
- FreeRTOS Setup
- Task Creation
- Task Scheduling
- RTOS Delay Functions

## Outcome
Successfully created and executed a FreeRTOS task for LED blinking.

---

# Experiment 7: Multiple FreeRTOS Tasks with Priorities

## Objective
To create and execute two FreeRTOS tasks with different priorities and analyze their effect on LED blinking behavior.

## Concepts Covered
- Multi-Tasking
- Task Priority
- Scheduler Behavior
- Real-Time Execution

## Outcome
Observed task execution differences based on assigned priorities.

---

# Experiment 8: External Interrupt with Task Synchronization

## Objective
To configure an external interrupt (EXTI) for a user button and use a FreeRTOS task notification or binary semaphore to synchronize an LED control task.

## Concepts Covered
- External Interrupts
- ISR Handling
- Binary Semaphore
- Task Notification
- RTOS Synchronization

## Outcome
Successfully synchronized LED control task using external interrupt events.

---

# Experiment 9: FreeRTOS Queue Communication with UART

## Objective
To implement inter-task communication using a FreeRTOS queue where one task generates or acquires sensor data and another task transmits the received data over UART.

## Concepts Covered
- FreeRTOS Queues
- Inter-Task Communication
- UART Communication
- Producer-Consumer Model

## Outcome
Successfully transferred data between tasks using queues and transmitted data through UART.

---

# Experiment 10: Counting Semaphore Resource Sharing

## Objective
To model a limited shared resource using a FreeRTOS counting semaphore and study access control when multiple tasks request the resource simultaneously.

## Concepts Covered
- Counting Semaphore
- Shared Resource Management
- Task Synchronization
- Resource Allocation

## Outcome
Successfully controlled access to shared resources among multiple tasks.

---

# Repository Structure

```text
RTOS-Project-Portfolio/
│
├── Experiment_01_GPIO_LED/
├── Experiment_02_Button_Interface/
├── Experiment_03_HCSR04/
├── Experiment_04_PWM/
├── Experiment_05_SuperLoop/
├── Experiment_06_FreeRTOS_LED/
├── Experiment_07_Task_Priority/
├── Experiment_08_EXTI_Semaphore/
├── Experiment_09_Queue_UART/
├── Experiment_10_Counting_Semaphore/
└── README.md
