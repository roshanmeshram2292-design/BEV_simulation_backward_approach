# EV Simulation in MATLAB  

This repository contains an Electric Vehicle (EV) performance simulation built in MATLAB/Simulink. The project focuses on evaluating EV drivetrain requirements under real-world driving conditions using standard duty cycles and determine the sizing of traction motor.  

## Features  
1. **Drive Cycles Implemented**  
   - WLTP (Worldwide Harmonized Light Vehicles Test Procedure)  

2. **Performance Analysis**  
   - Top speed estimation  
   - 0–100 km/h acceleration time  

3. **Outputs Generated**  
   - Torque vs. Time for WLTP  
   - Power vs. Time for WLTP  
   - Torque-Speed curve  
   - Power-Speed curve  
   - Efficiency map of the traction motor  

4. **Motor Sizing Insights**  
   - Maximum power requirement  
   - Maximum torque requirement  
   - Maximum speed requirement  

## Applications  
This simulation helps in:  
- Selecting appropriate traction motor specifications  
- Benchmarking EV drivetrain performance  
- Understanding system-level impacts of duty cycles on motor sizing  

## Tools  
- MATLAB/Simulink (script-based modeling and analysis)

## SIMULINK model
![image alt](https://github.com/roshanmeshram2292-design/BEV_simulation_backward_approach/blob/cb9bba5756b88177ef0afdb323b4d6d6a4730044/Result%20Images/Simulink_model.JPG)

## Results of EV simulation model
![image_alt](https://github.com/roshanmeshram2292-design/BEV_simulation_backward_approach/blob/7005ae2fa9c18abdadaa75d95516cd4cdd784fbc/Result%20Images/Motor_Power_Curve_WLTP.jpg)

![image_alt](https://github.com/roshanmeshram2292-design/BEV_simulation_backward_approach/blob/7005ae2fa9c18abdadaa75d95516cd4cdd784fbc/Result%20Images/Motor_Torque_Curve_WLTP.jpg)


## Result of Motor sizing model
![image_alt](https://github.com/roshanmeshram2292-design/BEV_simulation_backward_approach/blob/7005ae2fa9c18abdadaa75d95516cd4cdd784fbc/Result%20Images/Motor_Torque_v_Speed.jpg)

![image_alt](https://github.com/roshanmeshram2292-design/BEV_simulation_backward_approach/blob/7005ae2fa9c18abdadaa75d95516cd4cdd784fbc/Result%20Images/Motor_Power_v_Speed.jpg)

![image_alt](https://github.com/roshanmeshram2292-design/BEV_simulation_backward_approach/blob/7005ae2fa9c18abdadaa75d95516cd4cdd784fbc/Result%20Images/Motor_Efficiency_Map.jpg)

## How to use the model
1. Clone or download this repository.
2. Open MATLAB (R2024a or later recommended).
3. Navigate to the folder where the repository is saved.
4. Open the file **`EV_sim_script.mlx`** in MATLAB.
5. Click **Run** to execute the live script and see the simulation results.

6. For customised duty cycle, accleration and top speed change the respective parameters and excel spreadsheet as per requirement and follow the same above steps.

7. Same **'EV_sim_model.slx'** file can be used to run seperately for the different customised duty cycle. For drive cycle update the excel spreadsheet as required and change the "duty cycle case block" variable like [1, 2, 3]. This model can be used to estimate the approximate Battery capacity of vehicle, SOC % level for specifed duty cycle, Battery current etc.
