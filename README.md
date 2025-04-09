# Electric-Vehicle-Battery-and-Thermal-Simulation-Model-using-Simulink

This project presents a comprehensive Electric Vehicle (EV) model built using MATLAB Simulink. It simulates key components of an electric drivetrain, including energy storage, power electronics, motor control, and vehicle dynamics, enabling performance analysis under different drive cycles.

## Features

Total Blocks: 333

Subsystems: 34 modular and reusable components

Battery System: SOC estimation, discharge modeling

Electric Motor: PMSM model with torque/speed control

Power Electronics: Inverter & DC-DC converter integration

Vehicle Dynamics: Longitudinal model with road load forces

Regenerative Braking: Energy recovery and efficiency boost

Drive Cycles: Support for UDDS, WLTP, and custom profiles

Visualization: Real-time scopes and signal tracking

Configurable Parameters: Simulink ConfigSets for test scenarios

Thumbnail Preview: Auto-generated block diagram image


## Technologies Used

MATLAB R2023b

Simulink

Simscape Power Systems

Control System Toolbox


## Description

a) Developed a full-scale Electric Vehicle (EV) simulation model using MATLAB Simulink, encapsulating the core physical and electrical dynamics of an electric powertrain with a modular, scalable architecture.

b) The model includes 333 individual blocks and 34 subsystems, each representing specific functionalities such as the battery management system (BMS), electric motor drive, DC-DC converter, inverter, vehicle longitudinal dynamics, regenerative braking system, and driver control logic.

c) Simulated key components and energy flows:

   》Battery Pack: Modeled using a dynamic equivalent circuit to simulate SOC (State of Charge), voltage, and temperature behavior under varying load conditions.

   》Electric Motor & Controller: Incorporated a PMSM/BLDC motor with closed-loop torque and speed control logic using PID and lookup tables.

   》Power Electronics: Designed converter and inverter blocks with switching behavior to manage energy flow between the battery and motor.

   》Vehicle Dynamics: Simulated real-world driving scenarios including acceleration, deceleration, road load forces, and rolling resistance using vehicle mass, aerodynamic drag, and terrain input.


d) Integrated driving cycles such as UDDS and WLTP to simulate urban and highway conditions and assess energy efficiency, range, and response.

e) Implemented a regenerative braking system to analyze energy recovery and its impact on range extension.

f) Used Config Sets and Simulink Data Dictionary for parameter control, enabling rapid testing across different configurations and driving profiles.

g) Created visualization dashboards with Scopes and Simulink Data Inspector to monitor voltage, current, speed, torque, and SOC over time.

h) Ensured reusability and clarity by modularizing each component into well-structured subsystems with annotation and hierarchy navigation.

i) Packaged the model with a Simulink thumbnail image, and embedded metadata for version control, authorship, and documentation.

j) Gained hands-on experience with model-based design (MBD), system integration, and simulation debugging in a real-world EV control system context.


## Getting Started

1. Clone or download the repository.


2. Open the .slx file in MATLAB Simulink.


3. Run the model or adjust parameters in the Configuration Set.


4. View results using Scopes or Simulink Data Inspector.
