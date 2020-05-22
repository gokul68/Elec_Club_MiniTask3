# Elec_Club_MiniTask3
# PROJECT 1
## Problem Statement:
To implement a ring like in Green Lantern which lights up when you wear it up.

## Issues with the existing implementation:
It is implemented using a push button such that it triggers on when you wear it. This is painful as the push button constantly rubs our skin.

## Constraints:
Size and power. It should be small as the entire circuitry should be within the ring.

## My changes in implementation:
I would suggest that an IR transmitter receiver pair be used. We can reduce the size of the pins and have the be a reasonable size. It will be bigger than normal rings but manageable. The transmitter and receiver will be diametrically opposite to each other. The LED will turn on when the receiver does not receive a signal (meaning that a finger is obstructing it) and will be off when the receiver does receive a signal.

# PROJECT 2
## Problem Statement:
Here, an 18 DOF hexapod is to be implemented using Reinforcement Learning. In RL, it is important to know the state of the bot and we have to recreate it in the computer. So, this is what we want to achieve.

The three main aspects in this will be the sensors that collect the data and send it to the computer, the microcontroller, and wiring.

## Sensor:
I would suggest using an IMU sensor like [MPU6050](https://invensense.tdk.com/wp-content/uploads/2015/02/MPU-6000-Datasheet1.pdf). It contains a 3 axis MEMS accelerometer and a 3 axis MEMS gyro in a single chip. It also contains 16-bits analog to digital conversion hardware for each channel and has an input voltage range of 2.3-3.4V

## Microcontroller:
I would suggest using an Arduino MEGA if the budget permits, as we will require a lot pins since we are using a lot of sensors.

## Wiring:
Since we have 18 motors, there will be a lot of wiring and we will have to prevent tangling of wires. 

# PROJECT 3
## Problem Statement: 
An autonomous self-contained robot that can get to the centre of the maze in the shortest possible time.

## Components required: 
1. Ultrasonic sensor (HC-SR04) to detect obstacles (like the walls) so that it can turn.

2. Time of flight sensor which gives the distance travelled by the bot.

3. 6V DC Motor and Motor drivers.

4. Microcontroller: I would suggest using the Arduino Uno as it is cheap and within the size range and is not too heavy.

5. AA Batteries and a battery pack to power the Arduino and the motors.
