# Berke Girgin - Engineering Portfolio

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://linkedin.com/in/berke-girgin-099028236)
[![Portfolio](https://img.shields.io/badge/Portfolio-PDF-red.svg)](#) *(You can download the full PDF portfolio from the repository files)*

Welcome to my engineering portfolio repository. I am an **Electronics and Communication Engineer** specializing in Embedded Systems, Real-Time Control Theory, IoT, and Cloud Telemetry. This repository serves as a central hub for my technical projects, showcasing my expertise in translating theoretical concepts into robust hardware and software solutions.

---

## 🛠️ Core Competencies & Tech Stack
*   **Microcontrollers & SoCs:** ESP32, STM32 (ARM Cortex-M), ATmega8A (AVR), Arduino
*   **Software & RTOS:** Embedded C/C++, FreeRTOS, Bare-Metal Programming, Python
*   **Control Theory & DSP:** Cascade PID, Sensor Fusion (Complementary Filters), MATLAB, Simulink (MBD)
*   **Hardware Design:** Analog Circuit Design, PCB Logic, H-Bridge Motor Control, High-Voltage Safety Logic
*   **Communication & IoT:** Wi-Fi (UDP Telemetry), Bluetooth (UART Bridge), Modbus RTU, MQTT (HiveMQ)

---

## 🚀 Featured Projects

### 1. PID Controlled Self-Balancing Robot (ESP32)
*   **Tech Stack:** ESP32 (Dual-Core, FreeRTOS), C/C++, MPU6050 (IMU), NEMA17 Steppers, Wi-Fi UDP.
*   **Highlights:** Designed a Cascade PID architecture (250Hz inner PD, 20Hz outer PI). Implemented a Complementary Filter (99% gyro / 1% accel) for sensor fusion. Partitioned tasks using FreeRTOS to isolate the balance loop from network jitter.

### 2. High-Voltage Insulation Monitoring System (STM32)
*   **Tech Stack:** STM32, Embedded C, Unbalanced Bridge Circuit, Optical Relays, Hardware ADC.
*   **Highlights:** Safety-critical system for EV Battery Packs. Developed a 4-step real-time measurement algorithm using optical relays and complex algebraic models to detect ground faults and ensure human safety.

### 3. IoT-Enabled Temperature Control System (ATmega8A)
*   **Tech Stack:** ATmega8A, Bare-Metal C, Modbus RTU, MQTT (HiveMQ), Python (Tkinter).
*   **Highlights:** Engineered a 100ms hardware-timer ISR PID controller for a 12V heating element. Processed noisy J-Type thermocouple signals via Moving Average and NIST polynomial linearization. Developed a custom Modbus RTU slave stack.

### 4. Bluetooth Autonomous Robot with SLAM-Inspired Mapping
*   **Tech Stack:** Arduino UNO, HC-05 (Bluetooth), L298N, HC-SR04 (Ultrasonic), Python (Matplotlib).
*   **Highlights:** Created a logic-based autonomous avoidance routine. Built a multi-threaded Python Bridge Script to capture live telemetry over a UART bridge and visualize Dead Reckoning trajectories in real-time.

### 5. Model-Based ECU Start-Stop Controller
*   **Tech Stack:** MATLAB Simulink, Stateflow, Model-in-the-Loop (MIL) Testing.
*   **Highlights:** Developed an engine control unit using Model-Based Design (MBD). Implemented safety interlocking algorithms for gear/brake states and timer-based starter motor protection.

### 6. Analog Closed-Loop DC Motor Speed Controller
*   **Tech Stack:** Zero-MCU Hardware Logic, Op-Amps (LM358), Comparators (LM311), F/V Converters (LM2907).
*   **Highlights:** A purely analog control system. Converted optical encoder pulses to DC voltage and utilized differential amplifiers as the summing point to generate error signals for real-time PWM load compensation.

### 7. Hybrid Fake News Detection Engine (Machine Learning)
*   **Tech Stack:** Python, NLP (TF-IDF), Logistic Regression, K-Means Clustering.
*   **Highlights:** Applied NLP techniques to vectorize text. Trained supervised (Logistic Regression) classifiers and validated results using unsupervised (K-Means) clustering with Silhouette Score analysis.

---

## 📬 Contact
*   **Email:** brkgrgn2002@outlook.com
*   **Phone:** +90 531 610 44 48

> *"Let's Build Something Reliable."*
