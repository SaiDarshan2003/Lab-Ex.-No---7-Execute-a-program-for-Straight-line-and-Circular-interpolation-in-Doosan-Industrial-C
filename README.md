# Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
## Aim : To Execute a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio.

## Components Required:

*Doosan Industrial Collaborative Robot

*DRL (Doosan Robotics Language) Studio Software

### Theory 
INTERPOLATION

Interpolation, which is necessary for any type of programming, consists of generating data points between given coordinate axis positions. Within the Machine Control Unit (MCU), a device called an interpolator causes the drives to move simultaneously from the start to the end of the command. The interpolator is either an electronic hardware device for a NC system, or a software program for a CNC system. An interpolator provides two functions:

It calculates individual axis velocities to drive the tool along the programmed path at the given feed rate.

It generates thousands of intermediate coordinate points along the programmed path between the start point and the end point of the cut.

During positioning, all programmed axes move simultaneously at the specified feed rates until each axis has reached its destination. All drives start together, but without an interpolator individual destinations are reached successively according to the path traveled. However, an interpolator coordinates these axis motions in such a way that the programmed path is constantly maintained from the beginning to the end of the movement.

Linear and circular interpolation are most commonly used in CNC programming applications:

Linear interpolation is used for straight-line machining between two points.

Circular interpolation is used for circles and arcs.

Helical interpolation, used for threads and helical forms, is available on many CNC machines.

Parabolic and cubic interpolation are used by industries that manufacture parts having complex shape such as aerospace parts, and...

## Procedure:

Manipulate the end effector as per the given configuration. Movement Should Initiate in P1 and progress till the end point. Travel path should be in sequence as stated below.

Linear Interpolation


Circular Interpolation
### output
![175563842-4f34a7a0-31f5-4ff7-8b10-827c41013924](https://github.com/SaiDarshan2003/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/94692595/c1319c30-afb0-4dd5-8bdf-c7252764bfb5)
![175563638-e22b2a72-2c1e-4bc0-8d65-b08026477cd9](https://github.com/SaiDarshan2003/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/94692595/176cd3d7-5c48-4d8b-9b92-23e08d4f8a21)
![175563705-4a556742-5826-4ac8-aa0a-147ca515912f](https://github.com/SaiDarshan2003/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/94692595/70e2852f-902e-435f-a563-3016628aedf6)
![175563753-b2bf8fbc-018a-450e-aed0-0ca489356ea4](https://github.com/SaiDarshan2003/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/94692595/13f2b2fa-6b9b-402c-9086-7a1b2265f150)


### Results 


Thus,program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio is executed
