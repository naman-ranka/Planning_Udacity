# Motion Planning and Decision Making for Autonomous Vehicles

This is the project for the third course in the  [Udacity Self-Driving Car Engineer Nanodegree Program](https://www.udacity.com/course/c-plus-plus-nanodegree--nd213) : Motion Planning and Decision Making for Autonomous Vehicles.

**Project Summary**:

In this project completed on **Carla Simulator**, I successfully implemented the **Behavior Planner** and **Motion Planner** components for a self-driving car. The objective was to enable the car to navigate through scenarios such as avoiding static obstacles like parked cars, bicycles, and trucks, by executing "nudge" or "lane change" maneuvers. Additionally, the car had to handle various intersections (3-way, 4-way, and roundabouts) by stopping by default. To accomplish this, I developed **Finite State Machines (FSM)** for behavioral planning, performed static object collision checking, generated paths and trajectories using cubic spirals, and selected the best trajectory by evaluating a cost function that considers collision and proximity checks while staying close to the lane centerline. The successful completion of this project allowed me to showcase my expertise in implementing a complex planner for a self-driving car on the Carla Simulator.

![this is a image](/img/motionpass.jpg)


