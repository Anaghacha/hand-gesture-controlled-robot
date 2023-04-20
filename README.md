# hand-gesture-controlled-robot
_**Introduction**_
In the physical world, humans interact by the means of five basic senses.
However, gestures are a vital means of communication in the physical world
from earlier period, even before the invention of any language. In this era of
digital technology taking control of each complex tasks, interactions with
machines have become more vital than ever. The rising trend currently in the
field of science is artificial intelligence.
There are certain developments in area of human-machine interaction. One
common sort of communication is Gestures that are not solely restricted to face,
body and fingers but also hand gestures. So as to extend the utilization of robot
in places where conditions are not certain like rescue operations, robots can be
made to follow the instructions of human operator and perform the task
consequently. This proposes an integrated approach of tracking and recognition
of hands that is intended to be used as human robot interaction interface.
Therefore, we have made agesture-controlled robot using Arduino uno, ADXL
335 Accelerometer rf receiver and rf transmitter. This robot also consists object
detection feature which is implemented using ultrasonic sensors.
_**Motivation**_
Our motivation to work on this project came from a disabled person who was
driving his wheel chair by hand with quite a lot of difficulty. So we wanted to
make a device which would help such people drive their chairs without even
having the need to touch the wheels of their chairs.
_**Problem statement**_
The traditional wired buttons-controlled robot becomes very bulgy and it also
limits the distance the robot goes. The Wireless Handcontrolled Robot will
function by a wearable hand glove from which the movements of the hand can
be used as the input for themovement of the robot. The basic idea of our project
is to develop a system (Robot) which can recognize the Human Interactionwith
it to accomplish the certain tasks assigned to it. In our project we will design a
wearable Hand Glove which will contain thesensors mounted on it to capture
the movement of the hand and convert the raw mechanical data into electrical
form. This data willbe further processed and converted into an understandable
format for the Lilypad mounted on the Glove. This Lilypad will act as
atransmitter of the data for wireless communication purpose. Once the
transmitted data is received by the receiver module whichwill be connected to
the Microcontroller, it will be processed and further sent to the Microcontroller.
Microcontroller will deducethe commands and accordingly it will actuate the
motor drivers to control the Motors for various tasks on the robot.
_**Objective**_
The aim of the project is to develop a human machine interface used for control
robot arm. Our objective is to make this device simple as well as cheap so it can
be produced and used for number of purposes. The objective of this project is to
build a car that can be controlled by gesture wirelessly and also it can detect
obstacles in the path. In this project user is also able to control motions of the
car by wearing controller glove and performing predefined gestures
_**Methodology**_
The whole project is divided into two sections one is transmitter section and
other is receiver section. The brain of the robot is an Arduino Uno (Atmega32).
It is fed with a set of codes. The gestures/motion made by hand is recognized by
the acceleration measuring device called accelerometer (ADXL335). In transmitter part, an accelerometer, Arduino UNO, and a RF
transmitter unit is used. The Accelerometer above reads the X Y Z coordinates
when we make hand gestures. It then sends the X Y Z coordinates to the
Arduino. We don’t need the Z axis. We need only X and Y. The Arduino checks
the values of coordinates and then arduino convert the analog data to digital
which is further provided to RF pair transmitter.. And the transmitted data is
received by the RF transmitter. Then data is received by RF pair reciever and
passes to Motor Driver IC. Later the motor driver makes decision to turn the
motor in required direction .This robot is designed to recognize five sets of hand
gestures. Forward, backward, left, right, and stop.While the robot is moving , if
any obstruction is detected with the help of ultrasonic sensors then the buzzer
would ring alerting the user about the same .
