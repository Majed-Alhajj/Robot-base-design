# Robot-base-design
At the beginning I designed the Mecanum Wheels robot using Autodesk inventor also The base platform of this robot.

Here is the dimensions of the robot base:

Length: 300mm

Width: 156 mm

Height: 71mm

Thickness: 8 mm

The robot base is consisting of four mecanum wheels each one is attached on a stepper motor.

•	How Mecanum Wheels Work

A Mecanum wheel is a wheel with rollers attached to its circumference,
these rollers are positioned at 45-degree angle to the axis of rotation of the wheel.

This makes the wheel exert force in diagonal direction when moving forward or backward. 

As a result, by rotating these wheels in certain pattern, we utilize these diagonal forces and thus the robot can move in any direction we want.

We should use two types of mecanum wheels: (right handed and left handed),The difference between them is the orientation of the rollers and they must be attached in the robot in specific places, the rotation axis of each wheel should point to the center of the robot.

•	The function of each wheel to take a specific direction:

1.	To move forward: all four wheels move forward.

2.	To move backward: all wheels move backward.

3.	To move right: the right wheels will rotate inside the robot, while the left wheels will rotate outside the robot.

Note: the assembly of the robot base project compressed into rar file cause the github doesn't accept files have a size more than 25MPb
By using forcing analysis we will notice that, the resulting force due to the diagonally positioned rollers will make the robot move to the right.

4.	To move left: the left wheels will rotate inside the robot, while the right wheels will rotate outside the robot.

By using forcing analysis we will notice that, the resulting force due to the diagonally positioned rollers will make the robot move to the left.

Note: we also able to achieve movement in diagonal direction by rotating two wheels and stop the others.

![wheels direction](https://user-images.githubusercontent.com/85954773/125684648-f8d2e1bf-f360-4bcb-8adf-cbecdbac8538.jpg)

•	Mecanum wheel Installation:

The wheels are made out of two parts, outer and inner side which are secured together with some M3 bolts and nuts. They have 8 rollers each, and a shaft coupler specifically designed to fit the stepper motor.

Lets start the installation:

1-	Secure the Mecanum wheel by install the two sides of the wheel Opposite to each other and between them there is a shaft used to connect them then the shaft coupler is installed from the side that link the mecanum wheel with shaft of the stepper motor using four M3 bolts and nuts.

2-	For installing the rollers, first you need to slightly insert the M3 bolts through the holes located at the circumference outter side.

3-	Now you can insert the small M3 washer then insert the roller then insert a second washer on the other side of the roller and push the M3 bolts all the way to into the slot of the inner side of the wheel.

4-	Repeat this process for all rollers. 

Make sure all the rollers are moving freely.

•	Stepper motor Installation with the base :

Once the wheels are ready now we can move on with assembling the whole robot. 

1-	Attach the stepper motors to the base, for securing them in place use M3 bolts with a length of 12mm.

2-	Attach the wheels to the motor’s shafts, the shaft coupler have a slot for inserting an M3 nut, through which an M3 bolts can pass through and make the wheel secured to the shaft.

3-	Secure the top cover to the base, by attached the threaded rods on two corners of the base.

On the backside of the base, there is 20mm hole for attaching a power switch later on, as well as a 5mm hole for attaching an LED.

Note: I had uploaded the STL file into a rar file cause the github doesn't accept files over than 25Mb


