# Simscape Multi-Body Modeling and Trajectory Control

This project demonstrates the modeling and control of a multi-body system using Simscape, with trajectory planning for circular path following.

## Project Overview

The repository contains:
1. A Simscape multi-body model based on provided CAD geometry
2. Control system implementation for trajectory tracking
3. Results showing the system following a circular path

## Model Description

The multi-body model accurately represents the mechanical system from the provided CAD design, including:
- Rigid body dynamics
- Joint configurations
- Physical properties matching the original CAD

## Trajectory Control Implementation

The system implements:
1. **Circular Path Planning**: 
   - Smooth trajectory generation
   - Continuous position and velocity profiles
   
2. **Control System**:
   - Joint-level controllers
   - Trajectory tracking algorithms
   - Feedback compensation

## Results

### Multi-Body Model Simulation
![Multi-body Model Output](https://github.com/user-attachments/assets/292d1bb7-9285-46e6-ba40-eccddfe109be)

### Circular Trajectory Tracking
![Trajectory Following Output](https://github.com/user-attachments/assets/ac55eb45-597b-4daf-a2d3-d8900ba24e06)

## Requirements

- MATLAB R2020b or later
- Simscape Multibody
- Simulink
- Control System Toolbox

## Usage

1. Clone the repository
2. Open the main Simulink model file
3. Run the simulation
4. View results in the provided scopes and visualization blocks

## Customization

To modify the trajectory:
1. Edit the trajectory generation block parameters
2. Adjust the radius and speed in the path planning function
3. Update controller gains as needed for different dynamics

## License

This project is available for academic and research purposes. For commercial use, please contact the author.