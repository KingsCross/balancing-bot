# balancing-bot

## Intro

This is just at attempt at programming a two-wheeled robot driven using two BotBrain continuous servos and an Arduino Mega. It has an MPU 6050 IMU for finding error in pitch.

A PID controller is used.

Due to the rapid nature of this project, no effort was made to clean up the code. Perhaps I'll do this in the future :)

## Setup

Wire the Arduino and IMU boards as such:

Vcc : 3.3v-5v
GND: Ground
SCL: A5
SDA: A4
AD0: Ground
INT: Digital 2

## More Info:

IMU tutorial: https://turnsouthat.wordpress.com/2015/07/31/arduino-mpu6050-getting-ready/

Another similar IMU tutorial: https://diyhacking.com/arduino-mpu-6050-imu-sensor-tutorial/

Video on setting up IMU: https://www.youtube.com/watch?v=nlXqIe9-R7s

All credit on MPU 6050 DMP6 example code belongs to JEFF ROWBERG, who's repository can be found here: https://github.com/jrowberg/i2cdevlib/tree/master/Arduino/MPU6050
