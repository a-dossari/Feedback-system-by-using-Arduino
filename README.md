# Feedback system by using Arduino.

I designed a feedback system for two motors, when we rotate one of the motors (manually), the other one will move with the same rotation and at the same time.

As you can see in the file, when we hold the button, the angle of the lower motor will be changed when we drag the arrow of Potentiometer (equivalent to moving the arm manually), then the angle will be saved in the EEPROM memory, after that, the angle of the upper motor will be changed to the saved value (the angle of the lower motor) in the EEPROM memory. 


There is a video of a practical application of what I did, which is (see the video from 1:04 to 1:20):

<a href="http://www.youtube.com/watch?feature=player_embedded&v=P15V3UwmXnc
" target="_blank"><img src="http://img.youtube.com/vi/P15V3UwmXnc/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="480" height="360" border="10" /></a>

To build the circuit, I used:

- Arduino board.

- Two Servo motors.

- Potentiometer, to change the angle of the motor.

- Button, to turn on the system.
