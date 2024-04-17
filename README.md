# Matlab-Code

3/13/24 - Remote Control & Color Sensor
Implemented to go north, south and pick up grandma. Currently implementing color sensor.
Update: Added color sensor identification. Robot can now go through the maze and stop at certain colors. 

3/18/24 - Touch Sensor 
Currently adding touch sensor to be able to detect walls so robot can make turns accordingly.
In addition, working on navigation.
Currently working on code.
----------
![D6295E5D-5358-4934-BAF1-522472E21382_4_5005_c](https://github.com/elvis808/Matlab-Code-/assets/67409144/460c180a-5c00-44f7-87a8-1829b14e8966)

3/20/24 - Coding Navigation Cont. from 3/18/24
Implementing code to navigate EV3 robot to make turns and follow right side of the wall. The ultrasonic sensor senses wall by about 7-12 feet in distance so it is able to use the wall as a guide to go through the maze. Ended the class finally figuring out how to navigate around a structure without hitting it.

3/25 & 3/27 - Finalizing color sensor

Added color sensor to navigation code and was able to make it stop at certain colors. Stoping at red for a second and made it beep for blue and green. Iterations are being made to make the robot run smoother, and more efficiently. Demo will be linked below.

Youtube Link for current demo -> [(https://youtu.be/vt5fpE0bzSY](https://youtu.be/0KPv4HnEzPk))

4/1/24 - 4/3/24 - Addition of new touch sensor and use of bigger tires

Added big tired instead of small ones. Changing the tires helped immensely with navigation and turning. Turns have become quick and smooth as oppposed to the small tires we had before. Also added a new touch sensor which also helps with navigating through the maze. If left or right touch sensor is hit, it will back up and turn left. Small tires with the addition of the touch sensor gives a bigger surface to be be hit which enables us to navigate more efficiently. It does look like a fighter robot but we are contantly iterating through the design to make it better and better. 

Funny thing but we thought the entire maze had to be run through autonomously but we found out that we can move the robot at designated colors at green and blue. We only need the robot to be autonomous whhile it navigates through the maze. Making sure it stops at red, etc etc...

![966CD001-27DE-4AFF-BA68-9CA060713EE3](https://github.com/elvis808/Matlab-Code-/assets/67409144/68c37703-e70f-406d-9d05-56e633180c08)

4/8/24 - Implemented kill switch and tweak turn degree

Today was an important day. We took off one touch sensor and turned it into a kill switch to make the process easier. We implemented a test case to be able to pick up grandma at blue and drop off grandma. Lowered the color sensor to the ground so it better senses the color. It was also touching the right wheel so we pushed the claw that will be picking up grandma half an inch with another lego piece. Cable management overall has been solved with adding a few lego pieces to hold them together without interfering in the process of picking up grandma.

4/10/24 - Minor adjustments

We were able to throw in another if statement so that if the ultrasonic sensor get a little too close to the wall, it gives the right wheel a bit of a boost so it doesn't touch the wall. We then corrected the other tire and adjusted it so it pushes the same power as the right tire. After that if statement is finished, we go backinto the while loop and iterate through that. Were having issues with the code, we had to comment out the color sensors to make it turn right and making sure it turned smoothly. 

4/15/24 - Cont. current iteration and design process for smooth demo coming uo soon

Added another tire to the touch sensor so sending the wall become accurate and is able to make sharper turns. We also added pieces to the sides of the robot so for any mistakes with the turning or if it is not going straight, it helps straighten the robots trajectory. Next week is the demo so we are constantly iterating through the code and making sure it runs as it should and taking care of any problems that come our way.

4/17/24 - Pre demo integration

Today we are working on making the overall design better for demo next week. I believe that we have the concept down and we can go through the maze without any major errors. Switching small peices and making robot run smoothly is number 1 priority. 
