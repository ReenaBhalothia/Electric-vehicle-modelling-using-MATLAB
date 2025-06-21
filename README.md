# Two-Wheeler Electric Vehicle Modeling using MATLAB/Simulink

This project presents a dynamic simulation model of a two-wheeler electric vehicle (EV) built using MATLAB/Simulink. The model simulates the key components of an electric two-wheeler, enabling performance evaluation and system analysis under various operating conditions.

## Project Structure

- twowheeler.slx: Main Simulink file containing the complete EV model.
- README.md: Documentation describing the purpose, usage, and features of the model.

## Key Features

- Battery Modeling: Includes a basic battery pack to simulate charging and discharging behavior.
- DC Motor & Controller: Simulates the propulsion system using a DC motor with speed and torque control.
- Throttle Input: Allows speed control through variable throttle input.
- Load & Road Profile: Can be extended to include gradient and load variations.
- Real-time Response: Outputs include vehicle speed, motor current, battery SOC, and more.

## Use Cases

- Understanding the basic working of electric two-wheelers.
- Studying the impact of motor parameters on vehicle performance.
- Educational purposes for undergraduate electrical.
- Foundation for advanced projects like regenerative braking, BMS integration, or FOC control.

##  How to Run

1. Open MATLAB and navigate to the project folder.
2. Open the model:  
   ```matlab
   open('twowheeler.slx')
