# Buck-Boost Converter Control System Project

## About
This project explores the design and implementation of control systems for a buck-boost converter, typical of point-of-load voltage regulation in smartphones. It covers nonlinear modeling, linearization, state-space and transfer function representations, frequency-domain controller design, and observer-based full-state feedback control. Simulations in MATLAB/Simulink validate each model and controller, demonstrating performance under varying loads and battery voltages.

## Project Objectives
- Develop a nonlinear model of the buck-boost converter.
- Linearize the system and produce state-space and transfer function representations.
- Design controllers in both the frequency domain and using full-state feedback with an observer.
- Validate models and controllers through MATLAB/Simulink simulations.
- Evaluate performance under load changes and varying battery voltages.

## Key Features
- Nonlinear and linear modeling of buck-boost converters
- Controller design using Bode, Nyquist, and full-state feedback methods
- Observer-based state estimation
- Simulink simulations for model validation
- Handling of practical constraints such as duty-cycle saturation and load transients

## Files
- `MATLAB_Files.zip` — All MATLAB scripts and Simulink models

## Usage
1. Download or clone the repository.
2. Unzip `MATLAB_Files.zip`.
3. Open MATLAB and load the relevant `.m` scripts or Simulink `.slx` files.
4. Run simulations to validate models and controller performance.

## References
- MATLAB/Simulink documentation
- Course ELEC-3240: Control Systems
