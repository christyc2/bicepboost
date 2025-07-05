# BicepBoost

## Introduction
BicepBoost is an exoskeleton arm designed to assist individuals with limited arm mobility, such as those with physical impairments or neurological damage, with rehabilitation movements.

## Control System
The Arduino Nano reads analog values (along the X- and Y-axes) and a digital input from a handheld joystick to control the rotation speed and direction of a DC motor, which in turn controls the arm's motions.
For user safety, two limit switches are mounted at each end of the arm's range of motion. When the Nano reads a signal from either limit switch, it will hard stop the motor and briefly reverse its rotation for 0.2 seconds (to release the limit switch).
