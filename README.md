# SEA-Testbed
The Series Elastic Actuator(SEA) Testbed provides the software as well as the underlying Bachelor Thesis work for testing a SEA concept using torsional springs. This project provides static and dynamic test templates controlling components of this testbed and providing the means to record data for spring analysis and control strategies.

Created and first developed by Patrick Pably for the Robotic System Labor at technical univerity of vienna (TUW) 2024-2025

Abstract

This thesis presents the design, implementation, and validation of a modular testbed for 
evaluating torsional springs in Series Elastic Actuators (SEAs), targeting their application 
in compliant robotic joints. SEAs offer intrinsic mechanical compliance through a spring 
integrated in series between actuator and link, enabling improved force control, shock 
tolerance, and energy efficiency. The developed testbed supports a static configuration 
in which a force torque sensor is connected to the testbed, making the link rigid. This 
enables the deflection of a spring, and further the evaluation of stiffness and energy loss 
by capturing a springs hysteresis. Furthermore, in dynamic configuration, this sensor is 
removed, allowing the link rotate freely and evaluate a springs dynamic damping behavior 
as well as the evaluation of custom controller strategies.

The core objective was to build a low-cost, test platform with support for both static and 
dynamic spring testing to evaluate torsional springs for Series Elastic Actuators in elastic 
robot joints. It shall be able to accommodate different spring sizes and be modular in 
nature. Additionally, a real-time capable software framework to facilitate communication 
with an actuator and sensors shall be provided to enable testings and incorporate custom 
user parameters for various tests including static, dynamic and control evaluation.

The testbed was built and evaluated using three torsional springs generated with an 
open-source MATLAB-based spring design tool [1]. These springs have been optimized 
for fused deposition modeling 3D printing and manufactured out of PLA, PETG, and 
PC-ABS. Results showed that PC-ABS performs best across most metrics, demonstrating 
linear stiffness and minimal damping. However, the evaluation also revealed mechanical 
limitations, such as compliance in the drive shaft and communication delays in the 
actuator, which currently limit the system’s suitability for real-time control due to a low 
control frequency. Requiring replacement of the actuator to improve dynamic testing and 
a change of mechanical linkage or isolation of the spring measurement to improve the 
static test range. Nevertheless, the testbed provides a validated foundation for future 
research on compliant actuator design, control strategies, and spring optimization in 
robotic systems.
