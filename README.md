# focmotorcontrol
Implementing FOC motor control for BLDC motor for Xiaoyu Wang capstone at Carleton University. Software Group A. Created by: Nathan Allan

Config files were generated using the Modus Toolbox Device Configurator

Main file runs an open-loop test of the PWM implementation that will modulate PWM signals with a 120-degree offset to simulate motor behaviour. 

Algorithm does not yet include Hall sensor angle estimation or closed loop control from PI controllers. These parts were made by other group members.

Next Steps:
For deployment of the algorithm using closed-loop control, Hall sensor position estimation algorithm and duty cycle adjustment based on speed error
must be implemented. See Capstone Final Report for more information and next steps.
