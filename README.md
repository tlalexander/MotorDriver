# MotorDriver


This is a smart brushless motor driver board capable of precision servo-control (position and velocity control) of a low cost hobby brushless motor. This is managed by use of a magnetic angle sensor, and a feedback software that runs on the motor driver's onboard 64MHz ARM CPU.

The board is still under development, but the ultimate goal of this board is to enable lower cost robotics, especially for hobbyists.

Brushless motors have excellent torque characteristics, but complexity in their control has meant that complex gear reductions are typically needed to make use of these motors. With improved precision on motion control, larger motors can be used in lieu of complex gear trains, reducing system complexity.

Essentially, this board moves a mechanical problem to a software problem.

This is specifically quite helpful in the field of ultra low cost 3D printed robotics, where simpler mechanisms enable near zero cost robots to be built at home.

This board is designed to facilitate the development of these applications, but is not itself particularly low cost. If you like the idea of good quality brushless motor control for hobbyist robotics, please fork this project, simplify the design, and flood the market with cheap clones from China.


### Note 7/8/2016:
The current board design works with some changes. I haven't published the changes yet. If you want to make one, contact me first. I'd be happy to push the changes if someone wants to make some of these.


Features (planned)
------

* At least 1kW maximum power handling (depending on FETs used; theoretical max power for this FET package is 3kW).
* Current feedback for proper current-based motor control.
* Position feedback via external magentic encoder enables full closed loop control of low cost hobby brushless motors.
* Devices can be synchronized for six wire motor control (custom windings, linear motors, etc).
* Independent control of all bridges allows for brushed motor control with an additional half H bridge for other loads.
* USB interface allows easy control from a linux PC. Serial interface allows control from embedded systems such as Arduino.
* CPU runs Arduino code for easy portability.
* Multicolor LED to indicate status.

TODO
-----

* ~~Determine necessary device pinout and add properly wired headers.~~
* ~~Finish layout of current sense section.~~
* ~~Add jumper for battery power to CPU.~~
* ~~Full design review (is everything hooked up right?).~~
* ~~Finish all layout of Board V1.~~
* ~~Produce first test version.~~
* Full board test. (in progress)
* Write firmware for device.

Media
-----
It works! Check out the sweet video:
https://www.youtube.com/watch?v=cGBqlPRFbaQ


License
-----

This project is licensed under Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0), which is available at: http://creativecommons.org/licenses/by-sa/4.0/ If you use the files, please check them carefully - they may contain errors.
