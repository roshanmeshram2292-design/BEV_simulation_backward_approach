# EV Simulation in MATLAB  

This repository contains an Electric Vehicle (EV) performance simulation built in MATLAB/Simulink. The project focuses on evaluating EV drivetrain requirements under real-world driving conditions using standard duty cycles and determine the sizing of traction motor.  

## Features  
1. **Drive Cycles Implemented**  
   - WLTP (Worldwide Harmonized Light Vehicles Test Procedure)  

2. **Performance Analysis**  
   - Top speed estimation  
   - 0–100 km/h acceleration time  

3. **Outputs Generated**  
   - Torque vs. Time for WLTP and FTP-75  
   - Power vs. Time for WLTP and FTP-75  
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
![image alt](https://github.com/roshanmeshram2292-design/BEV_simulation_backward_approach/blob/7005ae2fa9c18abdadaa75d95516cd4cdd784fbc/Result%20Images/Simulink_model.JPG)

## Results of EV simulation model
![image_alt](https://github.com/roshanmeshram2292-design/BEV_simulation_backward_approach/blob/7005ae2fa9c18abdadaa75d95516cd4cdd784fbc/Result%20Images/Motor_Power_Curve_WLTP.jpg)

![image_alt](https://github.com/roshanmeshram2292-design/BEV_simulation_backward_approach/blob/7005ae2fa9c18abdadaa75d95516cd4cdd784fbc/Result%20Images/Motor_Torque_Curve_WLTP.jpg)

![image_alt](https://github.com/roshanmeshram2292-design/BEV_simulation_backward_approach/blob/7005ae2fa9c18abdadaa75d95516cd4cdd784fbc/Result%20Images/Motor_Power_Curve_FTP75.jpg)

![image_alt](https://github.com/roshanmeshram2292-design/BEV_simulation_backward_approach/blob/7005ae2fa9c18abdadaa75d95516cd4cdd784fbc/Result%20Images/Motor_Torque_Curve_FTP75.jpg)

## Result of Motor sizing model
![image_alt](https://github.com/roshanmeshram2292-design/BEV_simulation_backward_approach/blob/7005ae2fa9c18abdadaa75d95516cd4cdd784fbc/Result%20Images/Motor_Torque_v_Speed.jpg)

![image_alt](https://github.com/roshanmeshram2292-design/BEV_simulation_backward_approach/blob/7005ae2fa9c18abdadaa75d95516cd4cdd784fbc/Result%20Images/Motor_Power_v_Speed.jpg)

![image_alt](https://github.com/roshanmeshram2292-design/BEV_simulation_backward_approach/blob/7005ae2fa9c18abdadaa75d95516cd4cdd784fbc/Result%20Images/Motor_Efficiency_Map.jpg)
