# L2L-_Nantes_semester_Project

# Modified Kundur Two-Area System with Solar PV Farm for Typhoon HIL Simulation

![Power System Simulation](https://img.shields.io/badge/Simulation-Typhoon_HIL-blue) 
![License](https://img.shields.io/badge/License-MIT-green)

## 📖 Overview
This project modifies the classic Kundur two-area power system by replacing a conventional generator with a solar PV farm. The system is simulated using **Typhoon HIL** to study grid stability, dynamic responses, and renewable energy integration challenges. The work includes detailed modeling of voltage source converters (VSCs), LCL filters, diesel generators, and transmission lines.

## 🚀 Key Features
- **Solar PV Integration**: 1.1 MW PV farm with grid-following control and LCL filter.
- **Advanced Control Systems**: 
  - VSC control with PLL synchronization, dq-frame current control, and tie-line bias strategies.
  - Frequency setpoint control and droop mechanisms for stability.
- **Real-Time Simulation**: Implemented in Typhoon HIL for dynamic analysis of power flow, voltage regulation, and oscillation damping.
- **Hybrid System Analysis**: Combines diesel generators (1 MVA) and solar PV under variable load/generation scenarios.

## 📋 Project Structure


## ⚙️ Installation & Setup
### Prerequisites
- **Software**:
  - Typhoon HIL Control Center (v2023.1 or later)
  - MATLAB/Simulink (for LCL filter design)
- **Hardware**: Typhoon HIL 602+ or equivalent (for real-time simulation).

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/modified-kundur-pv.git


   
---

This README provides a structured overview of the project, setup instructions, key findings, and challenges. Customize repository links, licenses, or contributors as needed.
