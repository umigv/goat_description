## Synopsis

`urdf_bessie` contains the URDF and supporting files to describe our robot, informally known as Bessie.

## Motivation

Creating a URDF allows us two benefits: first, we can use the URDF in simulation with software like Gazebo to more accurately model the behavior of our robot, and second, we can use the URDF to generate an 2D Odometry sensor stream from wheel JointStates provided by encoders.

## Installation

Clone this repository into your `catkin` workspace, then run `catkin_make`. Optionally, run `catkin_make install` to install the package to your `catkin` workspace.

## Contributors

`urdf_bessie` is authored and maintained by Gregory Meyer.
