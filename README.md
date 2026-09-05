# Low Cost Three Phase Induction Motor Winding Failure Preventer

## 📌 Project Overview

This project presents a low-cost protection system designed to monitor abnormal operating conditions in three-phase induction motors and help prevent winding failures.

The system monitors electrical and thermal parameters and provides automatic protection by disconnecting the motor supply when critical abnormal conditions are detected.

## 🎯 Objectives

* Monitor three-phase motor operating conditions.
* Detect abnormal voltage and phase conditions.
* Monitor winding temperature.
* Provide Zero Voltage Protection (ZVP).
* Reduce the risk of motor winding damage.
* Develop a cost-effective motor protection system.

## ⚡ Key Features

* Zero Voltage Protection (ZVP)
* Three-phase supply monitoring
* Winding temperature monitoring
* Automatic relay-based protection
* Real-time parameter monitoring
* Low-cost implementation

## 💡 Proposed Innovations

### Winding Stress Index (WSI)

A monitoring approach to evaluate electrical and thermal conditions that may contribute to increased stress on motor windings.

### Early Thermal Pattern Recognition (ETPR)

A temperature-monitoring approach for identifying abnormal thermal behaviour at an early stage.

## 🧩 Hardware Components

* Arduino / ESP32
* Current Transformers (CTs)
* Negative Sequence Filter
* Relay Module
* Transistor Driver Circuit
* Bridge Rectifier
* Capacitor Filter
* Temperature Sensor
* LCD Display
* Three-Phase Supply
* Protection Components

## 💻 Software & Simulation Tools

* MATLAB / Simulink
* LTspice
* Proteus
* Tinkercad
* PSCAD
* Arduino IDE

## 🔧 Working Principle

The three-phase supply and motor operating parameters are continuously monitored using sensing circuits. The controller analyses the measured conditions.

When a critical abnormal condition is detected, the protection circuit activates the relay and disconnects the motor supply, helping to prevent further damage.

### System Flow

**Three-Phase Supply → Sensing & Protection → Controller → Monitoring → Relay → Motor**

## 📁 Repository Contents

```text
├── Code/
├── Circuit_Diagram/
├── Simulation/
├── Hardware_Images/
├── Project_Report.pdf
└── README.md
```

## 🔮 Future Scope

* IoT-based remote monitoring
* Cloud-based data logging
* Mobile application integration
* AI/ML-based fault prediction
* Advanced thermal pattern analysis
* Industrial-scale motor protection

## 👩‍💻 Project Domain

**Electrical & Electronics Engineering (EEE)**

**Areas:** Electrical Machines | Power Systems | Embedded Systems | IoT | Motor Protection

## 📜 Documentation

The complete project report is available in this repository as **Project_Report.pdf**.

---

*Developed as an academic engineering project with a focus on low-cost and intelligent induction motor protection.*
