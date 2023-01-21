  # ** Electrical-Vehicle-Motor-Temperature-Rise-Prediction **

# Introduction
Electric vehicles driven by permanent magnet synchronous motors(PMSM) are becoming more and more popular. Many
experimental studies have shown a drop in vehicle performance as well as thermal robustness at high motor temperatures,
but sensor-based temperature measurement such as infrared thermography[1] is technically and economically infeasible
due to the sophisticated motor structure and the difficult accessibility of the rotor. As a result, indirect measurements are
taken and the internal temperature is calculated using classic thermal models, which requires expert domain knowledge
and could hardly be transferred to general cases.



# Problem Statement
The aim of this project is to predict the Motor temperature of a permanent magnet synchronous motor (PMSM) using Different Regression models. As suggested in the explanatory notes of the dataset, sensor measuring all the different temperatures of the motor and the torque are not reliable nor economically feasible in commercial applications. A sufficiently accurate prediction model would therefore eliminate the need for sensor measurements to determine the permanent magnet temperature.

# Overview
PMSM is widely used in Electrical Vehicles ,robotics, machine tools, actuators, and it is being considered in high-power applications such as industrial drives and vehicular propulsion.

(1)Motor in Electrical Vehicles(EV's)
Research shows that temperature rise in the electric motor is one of the main components of an EV which negatively affects the performance of the EV . It leads to high failure rates, heating problems may catch fire and a shortened life span, which reduce the overall efficiency and performance of EVs.

(2)Motor Productivity and Maintenance
Being able to have strong estimators for the rotor temperature helps the automotive industry to manufacture motors with less material and enables control strategies to utilize the motor to its maximum capability. A precise torque estimate leads to more accurate and adequate control of the motor, reducing power losses and eventually heat build-up.On the rotor part, irreversible demagnetization of the permanent magnets can be caused by overheating, which represents an even more severe instance of motor damage.

# About Dataset
The data has been downloaded from a dataset in Kaggle provided by Paderborn University (Germany).The model was trained on the Electric Motor Temperature dataset which contains 1 million data collected from different testing sessions on the same PMSM with 2Hz sampling rate.

** Data Definition **
 ambient - Ambient temperature as measured by a thermal sensor located closely to the stator.
 
 coolant - Coolant temperature. The motor is water cooled. Measurement is taken at outflow.
 
 u_d - Voltage d-component
 
 u_q - Voltage q-component
 
 motor_speed - Motor speed
 
 torque - Torque induced by current.
 
 i_d - Current d-component
 
 i_q - Current q-component
 
 pm - Permanent Magnet surface temperature representing the Motor temperature. This was measured with an infrared thermography unit.
 
 stator_yoke - Stator yoke temperature measured with a thermal sensor.
 
 stator_tooth - Stator tooth temperature measured with a thermal sensor.
 
 stator_winding - Stator winding temperature measured with a thermal sensor.

# Using different Regression Algorithms the result can be applied to real-life situation in optimizing motor performance and giving out warnings when the motor temperature is abnormally high
