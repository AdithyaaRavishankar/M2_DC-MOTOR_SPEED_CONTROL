# REQUIREMENTS

## OBJECTIVE OF THIS PROJECT 

The main objective of this project is to show that the speed of a dc motor can be changed in many ways wherein in this case a potentiometer is used to control the speed which is considered one of the best and easy method to do so.

## INTRODUCTION

DC motor speed control is one of the most useful features of a motor. By controlling the speed of the motor you can change the speed of the motor as per your requirement and get the required performance.The speed control mechanism is applicable in many cases like controlling the movement of robotic vehicles, movement of motors in paper mills and the movement of motors in elevators where different types of DC motors are used. Speed control of DC motor is one of the most useful features of the motor.

## CATEGORY

Potentiometer is used to change the speed of the dc motor.



## COMPONENTS USED

1.atmega328p 

2.DC Motor

3.Connecting Wires

4.L293 Motor Driver

5.5V Voltage Source

6.Potentiometer

7.Oscope

## ADVANTAGES

1. DC motors offer highly controllable speed.
2. By changing the armature or field voltage it's possible to achieve wide speed variation and with this level of controllability, DC motors offer the precision required by a wide range of industry applications.
3. By controlling the speed of the motor you can change the speed of the motor as per your requirement and get the required performance.


## REQUIREMENTS


### High Level Requirements

|  ID   | Description | Status (Implemented/In Future) |
| ----- | ----------- | ------------------------------ |
| HLR 1 |    Dc motor was interfaced with Atmega328p using L293 |  Implemented  |
| HLR 2 |    Oscope interfaced with Atmega328p | Implemented |
| HLR 3 |    L293 interfaced using Atmega328p   | Implemented |
| HLR 4 |    Potentiometer interfaced using Atmega328p  | Implemented |


### Low Level Requirements

|  ID   | Description | Status (Implemented/ In Future) |
| ----- | ----------- | ------------------------------- |
| LLR 1 |    Viewing the output in oscope |  Implemented  |
| LLR 2 |    Speed of the dc motor is changed | Implemented |
| LLR 3 |    Potentiometer is used to vary the speed the dc motor | Implemented |


## DESIGN


### BLOCK DIAGRAM
![block3](https://user-images.githubusercontent.com/86227942/164874635-6107506f-f324-43e2-afa8-1859cc9f652a.png)




### DATA FLOW TRANSITION

![DATA3](https://user-images.githubusercontent.com/86227942/164874813-14d09f0e-5151-4ae4-9b60-71a557af0c03.png)




### FLOW CHART

![flow3](https://user-images.githubusercontent.com/86227942/164876677-9a8612e1-bd00-4c98-ae97-248a7a7eb384.png)




### STATE TRANSITION DIAGRAM

![state3](https://user-images.githubusercontent.com/86227942/164877567-77160bd5-d313-49a2-a524-519414a6d716.png)





### SCHEMATIC DIAGRAM

![simul2](https://user-images.githubusercontent.com/86227942/164802745-eafcb721-71cb-40e8-95c3-8a2e8bf916f4.png)

## 4W & H  (WHO,WHAT,WHEN,WHERE,HOW)

### * WHO:
 * In growing Automation field Robots play a vital role where speed controller play a major role in controlling them.
### * WHAT:
 * The intentional change of drive speed is known as speed control of a DC motor. We can control the speed of DC motor manually or through an automatic control device
### * WHEN:
 * These are used when there is requirement of controlling the speed. 
### * WHERE:
 * They are widely used in many places such as Elevator, Robots, Air Compressor,Electric Traction.
### * HOW:
 * By varying the Potentiometer one can easily change the speed to the desired level.

## * SWOT(STRENGTH,WEAKNESS,OPPORTUNITY,THREATS)

### * STRENGTH

 * They are suitable for low-speed torque.
 * They have adjustable speed.
 * They offer a wide range of speed control both below and above the rated speed.
 * They have a very high and strong starting torque.
 * They are more affordable.
 
### * WEAKNESS

 * High Intial Cost
 * Increased operation and maintenance cost due to the presence of commutator and brush gear.
 * Cannot operate in explosive and hazard conditions due to sparking occur at brush (risk in commutation failure).
 
### * OPPORTUNITY

 * It has regenerative braking capacity.
 * Good speed regulation.
 
### * THREATS

 * Drive produced more noise.
 * Costly arrangement is needed, floor space required is more.
 * Low efficiency at light loads.

