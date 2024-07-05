# Smart-Dustbin
A smart dustbin which can open and close its lid automatically as soon as someone comes near it to throw something.
The main concept behind the Smart Dustbin using Arduino project is Object Detection.
## Introduction 
It is a dustbin that open and close automatically when someone hand is near by it. It also move one place to another control by android phone(Bluetooth RC controller)

## Preview



https://github.com/Dhananjaykp/Tech/assets/137052868/155325f5-d3e9-4ac5-a4d3-9d720bae808f
## Components used

1. Arduino uno
   
2.	Ultrasonic Sensor

3.	Servo Motor

4.  DC motor

5.	L293Dmotor driver

6.	Jumper wires

7.	Led Bulbs

8.	Normal Dustbin
 
9.	9v Battery

10.	Charger 

11. Bluetooth RC Controller
    
## Circuit Diagram

![smart_dustbin_circuit](https://user-images.githubusercontent.com/56248007/119528865-31547380-bd9f-11eb-8535-9605b1661202.png)

![image](https://github.com/Dhananjaykp/Tech/assets/137052868/3a2e3b10-5a12-4656-8dbb-cbdfb079171c)

1. Arduino Uno :
Arduino Uno is a microcontroller board based on the ATmega328P (datasheet). It has 14 digital input/output pins (of which 6 can be used as PWM outputs), 6 analog inputs, a 16 MHz ceramic resonator (CSTCE16M0V53-R0), a USB connection, a power jack, an ICSP header and a reset button. It contains everything needed to support the microcontroller; simply connect it to a computer with a USB cable or power it with a AC-to-DC adapter or battery to get started.

2. Ultrasonic Sensor :
An ultrasonic sensor is a device that measures distance by using ultrasonic waves. It works on the principle of echolocation, similar to how bats navigate and hunt. The sensor emits ultrasonic waves, which travel through the air and reflect back to the sensor when they hit an object. By calculating the time it takes for the waves to return, the sensor can determine the distance to the object.

Key components of an ultrasonic sensor include:

Transmitter: Emits the ultrasonic waves.
Receiver: Captures the reflected waves.
Control Circuit: Processes the signal and calculates the distance.

Distance= (Speed of Sound×Time)/2
​
 


3.	Servo Motor :
A servo motor is a type of motor that can move to a specific position and hold that position accurately. It has a control system that helps it know exactly where to go and stay.

Key Points:
Moves Precisely: Can move to and stay at a specific position.
Uses Feedback: Has sensors to check and correct its position.
Common Uses: Found in robots, remote control cars, and drones smart dustbin 
Types: Includes different kinds like AC, DC, and continuous rotation servos.
​
 


4. DC Motor
A DC motor is a type of electric motor that uses direct current (DC) electricity to produce movement. It works by converting electrical energy into mechanical energy, which makes the motor's shaft rotate. This rotation can be used to drive various devices, from toys and home appliances to car parts and robots. DC motors are popular because they are simple to use and can easily have their speed controlled by adjusting the voltage.

Key Points:
Power Source: Uses direct current (DC) electricity from batteries or power supplies.
Operation: Electricity flows through the motor's windings, creating a magnetic field that turns the motor's shaft.
Speed Control: Speed can be easily adjusted by changing the voltage supplied to the motor.
Types: Common types include brushed and brushless DC motors.

5. L293Dmotor driver : The L293D is a popular motor driver integrated circuit (IC) used to control the direction and speed of DC motors. It acts as an interface between microcontrollers and motors, providing the necessary current and voltage to drive the motors. The L293D can control up to two DC motors or one stepper motor simultaneously.

Key Features:
H-Bridge Configuration: The L293D contains two H-bridge circuits, allowing it to control the direction of two DC motors independently. An H-bridge is a circuit configuration that enables a voltage to be applied across a load in either direction, making it ideal for motor control.
Current Handling: Each channel can handle up to 600mA of continuous current and can tolerate peaks of up to 1.2A.
Voltage Range: It operates with motor supply voltages from 4.5V to 36V.
Logic Compatibility: The input pins are compatible with standard TTL logic levels, making it easy to interface with microcontrollers like Arduino, Raspberry Pi, and others.

6. Jumper wires : Jumper wires are essential components in electronics and prototyping, used to create connections between various components on a breadboard or between different points on a circuit board.

7. Led Bulb :
A light-emitting diode (LED) is a semiconductor device that emits light when an electric current flows through it. When current passes through an LED, the electrons recombine with holes emitting light in the process. LEDs allow the current to flow in the forward direction and blocks the current in the reverse direction.

8. Normal Dustbin :
A dustbin is a container for collecting trash or garbage, keeping areas clean and organized. It can be made of plastic, metal, or other materials and comes in various sizes for indoor or outdoor use. Dustbins help manage waste by making disposal and recycling easier.

9. 9v Battery :
A DC 5 to 12V rechargeable battery for an Arduino Uno is a power source capable of being recharged and providing a direct current (DC) voltage within the range of 5 to 12 volts, suitable for powering an Arduino Uno microcontroller board. This type of battery can be based on various chemistries such as Lithium Polymer (Li-Po), Lithium-Ion (Li-Ion), or Nickel-Metal Hydride (NiMH), and is used to supply the necessary voltage and current to the Arduino for portable and remote applications.

10. Charger :
A charger for a DC 5 to 12V rechargeable battery used with an Arduino Uno is a device designed to replenish the battery's energy. It ensures the battery is charged safely and efficiently, matching the specific requirements of the battery chemistry (e.g., Li-Po, Li-Ion, NiMH). The charger typically includes features like voltage regulation, current limiting, and protection against overcharging, overheating, and short circuits. Depending on the battery type, the charger may have different connectors and charging protocols to maintain battery health and longevity.

11. Bluetooth RC Controller :

A Bluetooth RC controller app for a movable smart dustbin allows users to remotely control and interact with a smart dustbin using their smartphone or tablet.

Features
Control Interface:

Directional Controls: Virtual joysticks or arrow buttons to move the dustbin forward, backward, left, and right.
Lid Control: Buttons to open and close the lid.
Speed Control: Sliders or buttons to adjust the speed of movement.
