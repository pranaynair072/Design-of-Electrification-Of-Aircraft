⚡ Aircraft Electrification Analysis using MATLAB Scripts
This MATLAB-based project analyzes the electrification of a conventional aircraft propulsion system using custom-built scripts. It simulates power and energy performance, flight characteristics, and control logic under electrified conditions.

📄 Description
This project focuses on the electrification of an existing aircraft through MATLAB script-based simulations. Instead of using Simulink, all computations, dynamics, and system-level behavior are implemented via custom MATLAB scripts. The model calculates thrust, battery usage, energy efficiency, and altitude behavior based on electric propulsion retrofitting.

The simulation provides valuable insights into how electrification impacts flight dynamics, energy requirements, and system performance.

🚀 Getting Started
Requirements
MATLAB (R2024b or later recommended)
Basic MATLAB plotting and scripting knowledge

🧠 Clone the Repository
https://github.com/pranaynair072/MATLAB_Alpha-Electro

▶️ Run the Simulation
Open MATLAB and navigate to the cloned directory.
Run main_simulation.m — the central script to execute all computations.
The script will:
Simulate flight with electric propulsion
Display power, altitude, and energy metrics
Generate plots for system analysis

⚙️ Script Overview
🔌 Key Scripts
main_simulation.m: Main driver for the simulation
battery_model.m: Simulates battery charge/discharge dynamics
motor_model.m: Calculates electric thrust and efficiency
flight_dynamics.m: Evaluates aircraft altitude and velocity changes
control_logic.m: Optional script for PID or logic-based control inputs

✈️ Parameters Used
mass: Total aircraft mass (kg)
battery_capacity: Total energy available (Wh)
motor_power_rating: Maximum power output of the motor
drag_coefficient, lift_coefficient: Used for basic flight physics
initial_conditions: Starting altitude, velocity, etc.

📊 Outputs and Plots
Battery Cycle with respect to time
Range (km) vs Payload (kg)
Max Flight Time (hr) vs Payload (kg)
Battery Capacity (kWhr) vs Payload (kg)

📥 Contributions
This is a proprietary academic research project. Contributions or forks are not allowed without prior permission.
For collaboration or inquiries, contact the authors.

📄 License
This repository is licensed under a Proprietary Software License.
Unauthorized use, distribution, or modification is strictly prohibited.
