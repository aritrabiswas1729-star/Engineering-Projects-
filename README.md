#⚡ Aritra Biswas

<p align="center">
  <strong>M.Tech | System Control & Automation | IIT Guwahati</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/IIT%20Guwahati-M.Tech-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Control%20Systems-Research-purple?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Power%20Electronics-Research-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/EV%20%7C%20HESS-Applications-green?style=for-the-badge"/>
</p>

<p align="center">
  <a href="https://github.com/aritrabiswas1729-star">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/aritra-biswas-1b12/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:aritrabiswas1729@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

---

## 👋 About Me

I am an **M.Tech student in System Control and Automation at IIT Guwahati**, with a background in **Electrical and Electronics Engineering**.

My primary interests are:

- Control Systems
- Power Electronics
- Robust Control
- Electric Vehicles
- Hybrid Energy Storage Systems
- Renewable Energy
- Distributed / Consensus Control
- Optimization
- Robotics and Automation

I primarily work with **MATLAB/Simulink**, mathematical modelling, controller design, simulation, and optimization.

---

# 🔬 Research Interests

My current research direction focuses on:

> **Robust Control of Power-Electronic Converters with Applications to Hybrid Energy Storage Systems for Electric Vehicles.**

### Areas of Interest

```text
                 CONTROL SYSTEMS
                       │
          ┌────────────┼────────────┐
          │            │            │
          ▼            ▼            ▼
       Robust        LPV/H∞      Consensus
       Control       Control      Control
          │            │            │
          └────────────┼────────────┘
                       │
                       ▼
               POWER ELECTRONICS
                       │
          ┌────────────┼────────────┐
          │            │            │
          ▼            ▼            ▼
        DC-DC         HESS          EV
      Converters     Storage      Systems
````

---

# 🚀 Featured Projects

## ⚡ 1. Robust Control of HESS for Electric Vehicles

### Overview

Research-oriented work on **robust control of bidirectional DC-DC converters used in Hybrid Energy Storage Systems (HESS) for Electric Vehicles**.

### Key Points

* Robust control
* H∞ control
* LPV modelling
* Bidirectional DC-DC converters
* Battery–supercapacitor HESS
* DC-bus voltage regulation
* Converter uncertainty
* Wide operating-condition analysis
* MATLAB/Simulink simulation

### Keywords

`Robust Control` `H∞` `LPV` `HESS` `EV` `DC-DC Converter`

---

## 🔋 2. Control and Simulation of a 5-kW Wind-Solar Hybrid Energy System

### Overview

Simulation-based modelling and control of a **bidirectional DC/DC converter** for a 5-kW distributed wind-solar hybrid energy system with battery storage.

### Key Points

* Bidirectional buck/boost converter
* Battery charging and discharging
* Battery SOC estimation
* Energy-management system
* 300-V DC-bus regulation
* PWM generation
* Renewable generation/load power balancing
* MATLAB/Simulink simulation

### System Flow

```text
 Wind Energy ──────┐
                   │
                   ▼
              ┌─────────┐
 Solar PV ───►│ DC Bus  │◄── Load
              └────┬────┘
                   │
                   ▼
       Bidirectional DC/DC
             Converter
                   │
                   ▼
                Battery
                   │
                   ▼
                 SOC
              Estimation
                   │
                   ▼
          Energy Management
```

### Operating Modes

```text
Renewable Power > Load
        │
        ▼
 Battery Charging
        │
        ▼
      BUCK

Renewable Power < Load
        │
        ▼
 Battery Discharging
        │
        ▼
      BOOST
```

### Keywords

`Bidirectional Converter` `Wind-Solar` `Battery` `SOC` `Energy Management`

---

## 🤝 3. Cooperative Control of Heterogeneous DC/DC Boost Converters

### Overview

Development of a **distributed cooperative-control framework** for heterogeneous boost converters using a **mixed Negative Imaginary + Positive Real control approach**.

### Application

**Ship Degaussing System**

### Key Points

* Heterogeneous DC/DC boost converters
* Mixed NI + PR control
* Leader-following consensus
* Distributed cooperative control
* Communication graph
* Output-feedback control
* Current synchronization
* Time-varying reference tracking
* Disturbance analysis
* Switching-frequency investigation

### Control Architecture

```text
              Reference Current
                      │
                      ▼
             Communication
                  Network
                      │
                      ▼
          Distributed Controller
                      │
          ┌───────────┼───────────┐
          │           │           │
          ▼           ▼           ▼
       Boost 1     Boost 2     Boost N
          │           │           │
          ▼           ▼           ▼
        Coil 1      Coil 2      Coil N
          │           │           │
          └───────────┼───────────┘
                      │
                      ▼
              Current Consensus
```

### Main Objective

```text
y₁(t) → r₀(t)

y₂(t) → r₀(t)

   ⋮

yₙ(t) → r₀(t)

while

y₁(t) ≈ y₂(t) ≈ ... ≈ yₙ(t)
```

### Keywords

`Consensus Control` `NI+PR` `Boost Converter` `Multi-Agent Systems`

---

## 🧮 4. Optimal Economic Scheduling of Four Generators

### Overview

Formulation and solution of a constrained **economic scheduling problem for four electrical generators** using **CasADi and IPOPT**.

### Key Points

* Nonlinear optimization
* CasADi Opti framework
* IPOPT solver
* Four-generator scheduling
* Demand-supply equality
* Generator operating limits
* Ramp-rate constraints
* 10-hour scheduling horizon
* Constraint verification

### Optimization Flow

```text
        Demand Profile
              │
              ▼
      Generator Models
              │
              ▼
       Cost Functions
              │
              ▼
    Operating Constraints
              │
              ▼
       CasADi + IPOPT
              │
              ▼
    Optimal Generation
              │
              ▼
     Constraint Check
```

### Main Constraints

```text
Generation Balance:

x₁(k) + x₂(k) + x₃(k) + x₄(k) = d(k)


Generation Limits:

xᵢ,min ≤ xᵢ(k) ≤ xᵢ,max


Ramp-Rate:

|xᵢ(k) - xᵢ(k-1)| ≤ Ramp Limit
```

### Keywords

`Optimization` `CasADi` `IPOPT` `Economic Scheduling` `Power Systems`

---

## 🤖 5. TurtleBot3 Trajectory Tracking

### Overview

Development of a closed-loop **trajectory-tracking control system for TurtleBot3** using ROS 2 and MATLAB/Simulink.

### Key Points

* Differential-drive robot modelling
* ROS 2 communication
* Odometry feedback
* Quaternion-to-yaw conversion
* Circular trajectory generation
* Tracking-error calculation
* Coordinate transformation
* Nonlinear kinematic control
* Dynamic velocity control
* Closed-loop feedback

### Control Architecture

```text
             TurtleBot3
                  │
                  ▼
             ROS 2 /odom
                  │
                  ▼
           State Estimation
                  │
                  ▼
          Reference Comparison
                  │
                  ▼
           Tracking Errors
                  │
                  ▼
       Coordinate Transformation
                  │
                  ▼
        Nonlinear Controller
                  │
                  ▼
        Dynamic Controller
                  │
                  ▼
               /cmd_vel
                  │
                  ▼
             TurtleBot3
```

### Keywords

`ROS 2` `MATLAB` `Simulink` `Robotics` `Trajectory Tracking`

---

## ☀️ 6. Solar Battery Charger Using Buck Converter and MPPT

### Overview

Team project involving the design and implementation of a **solar battery charger using a buck converter and MPPT algorithm**.

### Key Points

* Maximum Power Point Tracking
* Buck converter
* Arduino UNO
* PWM control
* Solar-panel voltage/current measurement
* Battery charging
* SOC monitoring
* LCD parameter display
* 50-W solar panel
* 12-V lead-acid battery

### System Flow

```text
          Solar Panel
               │
               ▼
          Voltage /
       Current Measurement
               │
               ▼
             MPPT
          Algorithm
               │
               ▼
        Buck Converter
               │
               ▼
            Battery
               │
               ▼
          SOC Monitoring
               │
               ▼
              LCD
```

### Keywords

`MPPT` `Buck Converter` `Arduino` `Solar Energy` `Battery Charging`

---

# 🛠️ Technical Skills

## 🎛️ Control Systems

* Classical Control
* PID Control
* State-Space Control
* LQR
* Robust Control
* H∞ Control
* LPV Systems
* H∞ Loop Shaping
* Lyapunov Stability
* Negative Imaginary Systems
* Positive Real Systems
* Consensus Control
* Distributed Control

---

## ⚡ Power Electronics

* DC-DC Converters
* Buck Converters
* Boost Converters
* Bidirectional DC-DC Converters
* Small-Signal Modelling
* Average-Switch Modelling
* PWM Control
* Battery Systems
* Hybrid Energy Storage Systems
* DC-Bus Regulation
* Energy Management
* Renewable Energy Systems
* EV Power Electronics

---

## 🧮 Optimization & Mathematics

* Nonlinear Optimization
* CasADi
* IPOPT
* LMI Formulation
* Riccati Equations
* Transfer Functions
* State-Space Models
* Frequency-Domain Analysis
* Matrix Analysis
* Numerical Methods

---

## 🤖 Robotics & Automation

* ROS 2
* TurtleBot3
* Differential-Drive Robots
* Trajectory Tracking
* Feedback Control
* Nonlinear Control
* State Estimation
* MATLAB/Simulink

---

# 💻 Software & Tools

<p align="center">

<img src="https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white"/>

<img src="https://img.shields.io/badge/Simulink-FF6F00?style=for-the-badge&logo=mathworks&logoColor=white"/>

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>

<img src="https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>

<img src="https://img.shields.io/badge/ROS%202-22314E?style=for-the-badge&logo=ros&logoColor=white"/>

<img src="https://img.shields.io/badge/CasADi-555555?style=for-the-badge"/>

<img src="https://img.shields.io/badge/IPOPT-555555?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>

<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>

</p>

---

# 🔄 Engineering Workflow

```text
              Engineering Problem
                       │
                       ▼
               Mathematical Model
                       │
                       ▼
                 System Analysis
                       │
                       ▼
              Controller / Optimizer
                       │
                       ▼
                 MATLAB/Simulink
                       │
                       ▼
              Simulation & Testing
                       │
                       ▼
              Performance Analysis
                       │
                       ▼
                  Validation
```

### My Approach

```text
MODEL
  ↓
ANALYZE
  ↓
DESIGN
  ↓
SIMULATE
  ↓
STRESS TEST
  ↓
VALIDATE
```

---

# 📚 Current Learning

### Control

* Robust Control
* H∞ Control
* LPV Control
* H∞ Loop Shaping
* Distributed Control
* Consensus Control
* Stability Analysis

### Power & Energy

* Power Electronics
* DC-DC Converters
* Bidirectional Converters
* HESS
* Electric Vehicles
* Renewable Energy
* Battery Management
* Energy Management

### Computational Methods

* MATLAB
* Simulink
* Python
* CasADi
* Optimization
* LMI-based Controller Design

---

# 📂 Project Portfolio

| Project                                 | Domain                               | Main Tools              |
| --------------------------------------- | ------------------------------------ | ----------------------- |
| Robust HESS Control for EVs             | Robust Control / EV                  | MATLAB, Simulink        |
| 5-kW Wind-Solar Hybrid System           | Power Electronics / Renewable Energy | MATLAB, Simulink        |
| Heterogeneous Boost Converter Consensus | Distributed Control                  | MATLAB, Simulink        |
| Economic Scheduling of Four Generators  | Optimization / Power Systems         | MATLAB, CasADi, IPOPT   |
| TurtleBot3 Trajectory Tracking          | Robotics / Control                   | ROS 2, MATLAB, Simulink |
| Solar MPPT Battery Charger              | Renewable Energy / Embedded          | Arduino, C/C++          |

---

# 🎯 Career Interests

I am interested in opportunities involving:

**Control Engineering · Power Electronics · Electric Vehicles · Energy Storage · Robust Control · Advanced Control · Renewable Energy · Automation · Robotics · Model-Based Design · Research & Development**

---

# 📈 GitHub Activity

<p align="center">

<a href="https://github.com/aritrabiswas1729-star">
<img src="https://github-readme-stats-fast.vercel.app/api?username=aritrabiswas1729-star&show_icons=true&hide_border=true&theme=transparent" height="165"/>
</a>

<a href="https://github.com/aritrabiswas1729-star">
<img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=aritrabiswas1729-star&layout=compact&hide_border=true&theme=transparent" height="165"/>
</a>

</p>

<p align="center">

<a href="https://github.com/aritrabiswas1729-star/Engineering-Projects">
<img src="https://img.shields.io/badge/📂%20Engineering%20Projects-Explore%20Repository-0e75b6?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</p>

---

# 📫 Connect With Me

<p align="center">

<a href="https://github.com/aritrabiswas1729-star">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/aritra-biswas-1b12/">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="mailto:aritrabiswas1729@gmail.com">
<img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</p>

---

<p align="center">

<strong>Control Theory × Power Electronics × Energy Systems × Robotics</strong>

</p>

<p align="center">

<i>Building, modelling and controlling intelligent engineering systems.</i>

</p>
```
