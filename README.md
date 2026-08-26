# ⚡ Hi, I'm Andrés, an electronics engineering student 👋

<div align="center">
  <img src="Banner Ing Electronico.png" alt="Electronic Engineer Banner" width="100%" />
</div>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/andres-david-nazarith-gomez-67730a430)
[![Portfolio](https://img.shields.io/badge/Portfolio-Live-darkgreen?style=for-the-badge&logo=google-chrome)](https://github.com)
[![Email](https://img.shields.io/badge/Email-Contact_Me-red?style=for-the-badge&logo=gmail)](mailto:andresnazarit91@gmail.com)

---

### 👨‍💻 Professional Summary & AI / STEM Domain Focus
> **Electronic Engineering & Embedded Systems Specialist** with strong analytical background in dynamic modeling, digital signal processing (DSP), closed-loop control systems, RTL digital design in VHDL, and robust full-stack software development. 
> Proven experience in deductive problem-solving, bare-metal firmware debugging (C/C++), relational database architecture, and structured verification of technical logic tailored for **AI Model Training, Code Evaluation, and STEM Domain Annotation**.

---

## 🛠️ Hard Skills & Technical Stack

<table>
  <tr>
    <td width="30%"><strong>Category</strong></td>
    <td width="70%"><strong>Technologies, Frameworks & Tools</strong></td>
  </tr>
  <tr>
    <td><strong>Languages & HDL</strong></td>
    <td>
      <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" />
      <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" />
      <img src="https://img.shields.io/badge/VHDL-5C768D?style=flat-square" />
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
      <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>Backend & Databases</strong></td>
    <td>
      <code>Node.js</code> • <code>Express.js</code> • <code>PostgreSQL (Neon Serverless)</code> • <code>pg Connection Pooling</code> • <code>JSONB Schemas</code> • <code>RESTful APIs</code> • <code>Resend API</code> • <code>Background Cron Workers</code>
    </td>
  </tr>
  <tr>
    <td><strong>Embedded Systems & MCUs</strong></td>
    <td>
      <code>ESP32</code> • <code>ATmega328P</code> • <code>Arduino AVR</code> • <code>Bare-Metal Firmware</code> • <code>UART / SPI Protocols</code> • <code>Hardware PWM</code> • <code>ADC 10/12-bit</code>
    </td>
  </tr>
  <tr>
    <td><strong>FPGA & Digital Logic</strong></td>
    <td>
      <code>Intel/Altera Cyclone V (DE1-SoC)</code> • <code>FSM (Moore Machines)</code> • <code>Modular Hierarchical Design</code> • <code>BCD & 7-Segment Encoders</code>
    </td>
  </tr>
  <tr>
    <td><strong>DSP & Control Systems</strong></td>
    <td>
      <code>Fast Fourier Transform (FFT)</code> • <code>Butterworth Digital Filters (filtfilt)</code> • <code>Euler-Lagrange Dynamic Modeling</code> • <code>Laplace Domain Analysis</code> • <code>PID Control + Anti-Windup</code> • <code>System Identification (ωn, ζ)</code>
    </td>
  </tr>
  <tr>
    <td><strong>EDA, Dev & Simulation Tools</strong></td>
    <td>
      <code>Intel Quartus Prime</code> • <code>VS Code + PlatformIO</code> • <code>NI Multisim</code> • <code>LTSpice</code> • <code>Proteus</code> • <code>Git & GitHub</code> • <code>NumPy / SciPy / Matplotlib</code>
    </td>
  </tr>
  <tr>
    <td><strong>Power & Instrumentation</strong></td>
    <td>
      <code>Digital Oscilloscope</code> • <code>Active Op-Amp Filters (Sallen-Key)</code> • <code>Buck DC-DC Converters</code> • <code>Power MOSFETs (IRFZ44N)</code> • <code>Signal Conditioning</code>
    </td>
  </tr>
</table>

---

## 🚀 Featured Engineering Projects

### 📌 1. Aerodynamic Twin-Rotor Seesaw: Dynamic Modeling & Closed-Loop PID Control
* **Domain:** Nonlinear Dynamic Systems, Classical Control & Embedded C++
* Formulated and experimentally validated the **1-DOF nonlinear dynamic model** of a dual-motor thrust balance incorporating **Euler-Lagrange equations** and **Actuator Disk Aerodynamic Theory**.
* Designed and deployed a discrete **PID controller with trapezoidal anti-windup** and first-order finite backward differences for precise angular trajectory regulation.
* **Results & Performance:** Achieved **99.86% model accuracy** against real hardware data (simulated overshoot $M_p = 14.04\%$ vs. experimental $M_p = 14.06\%$, settling time $t_s = 3.8\text{ s}$, and zero steady-state error $e_{ss} = 0$).

---

### 📌 2. Real-Time RLC Signal Acquisition & Digital Signal Processing (DSP) Pipeline
* **Domain:** Virtual Instrumentation, Data Acquisition & Scientific Computing
* Developed a high-throughput instrumentation platform for transient response characterization of second-order underdamped RLC systems.
* Programmed an **ESP32** continuous ADC sampling pipeline operating at **2 kHz**, streaming acquisition arrays into a **Python (NumPy/SciPy)** analytical pipeline.
* Designed a **4th-order zero-phase digital low-pass Butterworth filter** and computed real-time **Fast Fourier Transforms (FFT)**, suppressing high-frequency switching noise and identifying natural frequency ($\omega_n$) and damping factor ($\zeta$).

---

### 📌 3. Hierarchical RTL Architecture in VHDL for FPGA (DE1-SoC Cyclone V)
* **Domain:** Reconfigurable Hardware, Synchronous Logic & Communication Protocols
* Synthesized modular VHDL hardware architecture for the **Intel Cyclone V FPGA** operating with a 50 MHz base oscillator clock.
* Implemented a **10° resolution servomotor position controller** with integrated BCD to 7-segment display logic and custom 50 Hz PWM generator ($0.5\text{ ms} - 3.2\text{ ms}$).
* Engineered a fully synchronous **SPI Master interface** for an external 12-bit ADC, featuring configurable frequency prescalers and an overlapping-sequence Moore FSM detector.

---

### 📌 4. BarberGold: Full-Stack Automated Booking & Business Management System
> 🔗 **Live URL:** [barbergold.com](https://www.barbergold.com.co/)

* **Domain:** Cloud Architecture, Serverless Databases, Backend Engineering & Asynchronous Workflows
* **Solely engineered and architected** a commercial scheduling and business operations platform from scratch utilizing **Node.js, Express.js, and Serverless PostgreSQL (Neon)** via connection pooling (`pg`).
* **Designed and structured** an ACID-compliant relational schema supporting staff availability, dynamic service durations, and business rules using semi-structured **JSONB** attributes.
* **Engineered** asynchronous event pipelines with **Resend API** for real-time transactional emails and built standalone **Cron Workers** for background schedule polling and automated appointment reminders.
* **Delivered and deployed** the full end-to-end solution for commercial production, handling database migrations, API error handling, and concurrency locks.

---

## 🎯 Technical Verification & ATS Keywords
```text
Sistemas Embebidos | Embedded Systems | VHDL | FPGA | C/C++ | Bare-Metal Firmware | 
Digital Signal Processing (DSP) | Fast Fourier Transform (FFT) | PID Control | 
Mathematical Modeling | Euler-Lagrange | Finite State Machines (FSM) | ADC 12-bit | 
SPI Protocol | Pulse Width Modulation (PWM) | Butterworth Filter | Full-Stack Development | 
Node.js | Express.js | PostgreSQL | Neon Serverless | Database Design | Cron Workers | 
REST APIs | Resend API | PlatformIO | Quartus Prime | ESP32 | ATmega328P | 
Circuit Simulation | Deductive Logic | Data Annotation | AI Model Training (STEM)
