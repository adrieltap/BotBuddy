## BotBuddy

Adriel Taparra

Milan Patel

 

# Project Name

# BotBuddy

Abstract

We are planning on creating an RC car with auto breaking capabilities. The vehicle will be controlled using a remote controller. To add the auto break, we will use an Ultra-Sonic Sensor, specifically the HC-SR04 to detect objects that are in front of the vehicle. For our RF transmitter and receiver, we will use [Insert part here]. Our motors will be [Insert Part here]. We will also need a battery [Insert Part Here] to be able to control the car since it will be wireless.  We will also need wheels, a chasis, and a servo motor.

# Block Diagram



![ECE395Car drawio](https://github.com/adrieltap/BotBuddy/assets/142434056/69070647-e051-4cde-ae23-c610b9f64e70)




# Project Goals

During our first demo, we want to able to have a moving car using the remote controller. It should be able to forward, back, left and right.

In the final demo, we want to be able to add these extra features to the car, such as the automatic breaking and maybe add some LEDs that would tell us the state of the vehicle.

# Low Level Coding

We plan on using the HAL functions, PWM and GPIO for the communications necessary. For the remote control, we will need to code how the motors will move, its speed and its angle based on the input given from the transmitter. For the auto breaking, we will need to code and decide when the car should stop as an object in the way gets closer. We are planning on using a certain range of values for the distance, so that the car can slowly decelerate instead of abruptly stopping when an object gets in the way.





