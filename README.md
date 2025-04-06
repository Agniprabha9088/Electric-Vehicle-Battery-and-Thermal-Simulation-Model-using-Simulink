# Electric-Vehicle-Battery-and-Thermal-Simulation-Model-using-Simulink

This project presents a simulation model for analyzing the electrical and thermal performance of a lithium-ion battery system used in electric vehicles (EVs). The model has been customized by Ancd to ensure uniqueness in structure, parameters, and component arrangement.

Model Overview:

The simulation is built in MATLAB Simulink and consists of the following key subsystems:

PowerStorageUnit: A customized battery model representing the dynamic behavior of lithium-ion cells under varying load conditions.

EnergyInteractionSystem: A subsystem integrating the thermal and electrical models to simulate how heat affects battery efficiency.

HeatManagementBlock: Models the thermal characteristics of the system, including ambient temperature effects, heat flow, and thermal mass.

DynamicVoltageInjector: Controls the voltage input dynamically to simulate real-world EV scenarios.

Custom parameter values have been set for internal resistances, cell counts, and temperature conditions. The block layout and naming conventions have been updated to reflect a novel design logic.

Additional Features:

Intermediate signals are visualized using Scopes.

Extra annotations are included for clarity.

Ready for future extensions like SoC estimation or cooling system design.


Conclusion:

This project provides a modular and realistic approach to modeling EV battery systems with thermal feedback, suitable for further optimization and integration with full vehicle simulations.
