# BLDC motor ESC
 This is a PCB that hosts at its core a STM32G474 Microcontroller to control a 5010 BLDC motor. 
 It is rated upto 20A current. 
 Each of the three phases contain 2 SIR182DP-T1-RE3 and a IR2103STRPBF gate driver. A bemf and curent measurement is performed for
 each phase. 
 An AS5047P magnetic encoder measures the rotary angle of the motor. 
 The aim of the project is to be able to perform FOC control. 
 The board also has a TCAN3414 CAN transciever IC to enable CAN bus communication. 
 The PCB will eventually be part of a robotic actuator. 
