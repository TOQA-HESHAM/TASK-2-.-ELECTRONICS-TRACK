TASK-2-.-ELECTRONICS-TRACK

General Objective of the Task:
To implement an electronics project using Tinkercad Circuits that aims to:

Control six servo motors using an Arduino Uno board.

Program a synchronized movement for all servos that simulates a robot-like behavior.

Learn how to connect and operate multiple electronic components simultaneously.

Design a basic walking algorithm for a humanoid robot using servo motors.


Steps to Implement the Task:
Create a new circuit project in Tinkercad Circuits.

Add the following components to the circuit:

One Arduino Uno board.

Six Servo Motors.

One Breadboard to distribute power and ground.

Connect the servos to the Arduino as follows:

All VCC (power) pins connected to the 5V pin on Arduino via the Breadboard.

All GND (ground) pins connected to the GND pin on Arduino via the Breadboard.

Signal pins of the six servos connected to digital pins D2 to D7.

Write the Arduino code in the code editor:

Include the <Servo.h> library to control servos.

Perform a Sweep movement on all six servos for 2 seconds.

After that, set all servos to hold at 90 degrees.

Start the simulation and observe:

The servos should move smoothly back and forth.

After 2 seconds, they should stop and hold at 90°.



Write a walking algorithm:

Create a simple step-by-step algorithm to simulate how a humanoid robot walks using servo motors.

The algorithm should describe how each leg is lifted, moved forward, and placed back down.

