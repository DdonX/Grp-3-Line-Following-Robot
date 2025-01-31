# Grp-3-Line-Following-Robot

A line-following robot is a type of autonomous robot designed to detect and follow a predetermined path, typically marked by a line on the ground. This project involves using sensors to track the line and control the robot's movement accordingly. 

To set up a line-following robot, you will need the following components: a chassis, DC motors, wheels, a motor driver (like L298N), an Arduino or microcontroller, line sensors (like infrared sensors), a power supply, and jumper wires. 

Begin by assembling the chassis, attaching the DC motors and wheels to it. Connect the motor driver to the motors and the Arduino. The motor driver acts as an interface between the Arduino and the motors, allowing you to control the direction and speed of the motors. 

Next, set up the line sensors. These sensors detect the contrast between the line (usually black) and the surface (usually white). Position the sensors at the front of the robot, ensuring they are close to the ground for accurate detection. Connect the sensors to the Arduino, which will read the sensor outputs.

Once the hardware is set up, you will need to install the Arduino IDE on your computer to write and upload the code. The code will read the sensor values and control the motors based on whether the robot is on the line or off it. Typically, if a sensor detects the line, the robot will adjust its motors to steer back onto the line.

Dependencies for this project include the Arduino IDE and any necessary libraries for motor control and sensor management, which can usually be found within the IDE or online. Once everything is set up and programmed, your robot should be able to autonomously follow a line, making adjustments as needed to stay on track.
