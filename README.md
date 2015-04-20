# PiCopter2
My second attempt at making a Raspberry Pi Quadcopter. 

Since my first Quadcopter was nothing more than a glorified lawn mower, I wanted to take a second crack at it. Rather than change my first repository I wanted to start from scratch. This time I will be using a lighter frame and lighter materials all around. I am going to add a proximity sensor and other features like actually flying. 

# Materials
    RPi 2
    Arduino Uno
    Proximity sensor
    4 brushless motors
    4 ESC's
    gyroscope
    LiPo Battery
    Portable Cell Phone Charger
    Carbon Fiber Frame
    PS3 Controller
    Bluetooth Dongle

# Design
The code was again written in Python except for the Arduino part. The RPi received input from the PS3 controller and sent that info to the Arduino which then controlled the motors. The Proximity sensor was designed for an Arduino so that was easy to implement by having it talk directly to the Arduino. The build went very similar to the previous Quadcopter I made with the slight difference being that I purchased the frame this time to keep the weight down and added a gyro and proximity sensor.
