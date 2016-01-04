# MotorDriver


This is a smart brushless motor driver board capable of precision servo-control (position and velocity control) of a low cost hobby brushless motor. This is managed by use of a magnetic angle sensor, and a feedback software that runs on the motor driver's onboard 64MHz ARM CPU.

The board is still under development and is far from complete, but the ultimate goal of this board is to enable lower cost robotics, especially at the very low cost end for hobbyists.

Brushless motors have excellent torque characteristics, but complexity in their control has meant that complex gear reductions are typically needed to make use of these motors. With precise position control, gear reductions can be simplified, reducing mechanical complexity.

Essentially, this board moves a mechanical problem to a software problem.


Features (planned)
------

At least 1kW maximum power handling (depending on FETs used; theoretical max power for this FET package is 3kW).
Current feedback for proper current-based motor control.
Position feedback via external magentic encoder enables full closed loop control of low cost hobby brushless motors.
Devices can be synchronized for six wire motor control (custom windings, linear motors, etc).
Independent control of all bridges allows for brushed motor control with an additional half H bridge for other loads.
USB interface allows easy control from a linux PC. Serial interface allows control from embedded systems such as Arduino.
CPU runs Arduino code for easy portability.
Multicolor LED to indicate status.


License
-----

This project is licensed under Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0), which is available at: http://creativecommons.org/licenses/by-sa/4.0/ If you use the files, please check them carefully - they may contain errors.
