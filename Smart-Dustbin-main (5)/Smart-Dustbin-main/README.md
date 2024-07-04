# Smart-Dustbin
A smart dustbin which can open and close its lid automatically as soon as someone comes near it to throw something.
The main concept behind the Smart Dustbin using Arduino project is Object Detection.
## Introduction 
It is a dustbin that open and close automatically when someone hand is near by it. It also move one place to another control by android phone(Bluetooth RC controller)

## Preview



https://github.com/Dhananjaykp/Tech/assets/137052868/155325f5-d3e9-4ac5-a4d3-9d720bae808f
## Components used


1.	Ultrasonic Sensor

2.	Servo Motor

3.  DC motor

4.	L293Dmotor driver

5.	Jumper wires

6.	Led Bulbs

7.	Normal Dustbin
 
8.	9v Battery

9.	Charger 


## Circuit Diagram

![smart_dustbin_circuit](https://user-images.githubusercontent.com/56248007/119528865-31547380-bd9f-11eb-8535-9605b1661202.png)

![image](https://github.com/Dhananjaykp/Tech/assets/137052868/3a2e3b10-5a12-4656-8dbb-cbdfb079171c)

1. Ultrasonic Sensor :
An ultrasonic sensor is a device that measures distance by using ultrasonic waves. It works on the principle of echolocation, similar to how bats navigate and hunt. The sensor emits ultrasonic waves, which travel through the air and reflect back to the sensor when they hit an object. By calculating the time it takes for the waves to return, the sensor can determine the distance to the object.

Key components of an ultrasonic sensor include:

Transmitter: Emits the ultrasonic waves.
Receiver: Captures the reflected waves.
Control Circuit: Processes the signal and calculates the distance.

Distance= (Speed of Sound×Time)/2
​
 


2.	Servo Motor :
A servo motor is a type of motor that can move to a specific position and hold that position accurately. It has a control system that helps it know exactly where to go and stay.

Key Points:
Moves Precisely: Can move to and stay at a specific position.
Uses Feedback: Has sensors to check and correct its position.
Common Uses: Found in robots, remote control cars, and drones smart dustbin 
Types: Includes different kinds like AC, DC, and continuous rotation servos.
​
 


3. DC Motor
A DC motor is a type of electric motor that uses direct current (DC) electricity to produce movement. It works by converting electrical energy into mechanical energy, which makes the motor's shaft rotate. This rotation can be used to drive various devices, from toys and home appliances to car parts and robots. DC motors are popular because they are simple to use and can easily have their speed controlled by adjusting the voltage.

Key Points:
Power Source: Uses direct current (DC) electricity from batteries or power supplies.
Operation: Electricity flows through the motor's windings, creating a magnetic field that turns the motor's shaft.
Speed Control: Speed can be easily adjusted by changing the voltage supplied to the motor.
Types: Common types include brushed and brushless DC motors.

4. L293Dmotor driver : The L293D is a popular motor driver integrated circuit (IC) used to control the direction and speed of DC motors. It acts as an interface between microcontrollers and motors, providing the necessary current and voltage to drive the motors. The L293D can control up to two DC motors or one stepper motor simultaneously.

Key Features:
H-Bridge Configuration: The L293D contains two H-bridge circuits, allowing it to control the direction of two DC motors independently. An H-bridge is a circuit configuration that enables a voltage to be applied across a load in either direction, making it ideal for motor control.
Current Handling: Each channel can handle up to 600mA of continuous current and can tolerate peaks of up to 1.2A.
Voltage Range: It operates with motor supply voltages from 4.5V to 36V.
Logic Compatibility: The input pins are compatible with standard TTL logic levels, making it easy to interface with microcontrollers like Arduino, Raspberry Pi, and others.

5. Jumper wires : Jumper wires are essential components in electronics and prototyping, used to create connections between various components on a breadboard or between different points on a circuit board.
