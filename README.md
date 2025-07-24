# airflow-distribution-manifold-cfd-analysis

This project simulates internal airflow distribution inside a 3-outlet manifold. The goal is to achieve uniform flow across all outlets under a total inlet flow of 3 L/min. The study was performed using ANSYS Fluent and ANSYS Mechanical meshing tools, focusing on pressure drop, streamline visualization, and outlet velocity profiles.


---

## Problem Definition

- Air enters the manifold at a flow rate of **3 L/min**.
- Goal: Achieve **uniform outlet flow** (±10% variation allowed).
- Outlet gauge pressure is set to **0 Pa** at all three exits.
- Evaluate if current manifold design meets the uniformity requirement.

---

## Simulation Setup

| Parameter              | Value                          |
|------------------------|--------------------------------|
| Flow rate              | 3 L/min                        |
| Boundary conditions    | Velocity inlet, pressure outlet|
| Solver                 | Steady-state, laminar/turbulent|
| Meshing Tool           | ANSYS Mechanical               |
| Solver Tool            | ANSYS Fluent                   |

---

## Project File

📎 [Click here for Google Drive simulation files](https://drive.google.com/file/d/1dnlbaYpnEfRQgRRIpOQMlf4rmvxsGOAk/view?usp=sharing)

---

## Key Results

- Inlet velocity and pressure gradient properly resolved.
- Outlet flow rates varied between X%–Y% across branches.
- Observed backflow and turbulence in certain branches due to geometry.

---

## Purpose

This project was completed to practice flow field distribution analysis inside a manifold, simulating real-world intake/exhaust systems.

I'm a **Mechanical Engineering Master's student** focused on **CFD and FEA**. This project supports my portfolio as I pursue a role in:
- HVAC or automotive flow systems
- Turbomachinery
- Thermal-fluid systems

---

> 💬 Feel free to connect (https://www.linkedin.com/in/mehmet-sabri-aksoy/) or message me for collaboration or discussion.
