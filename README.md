# Where-Am-I
Udacity Robotics ND: term II : Localisation project 
Project Overview
Welcome to the localization project! In this project, you will learn to utilize ROS packages to accurately localize a mobile robot inside a provided map in the Gazebo and RViz simulation environments.

Over the course of this lesson, you will learn about several aspects of robotics with a focus on ROS, including -

Building a mobile robot for simulated tasks.

Creating a ROS package that launches a custom robot model in a Gazebo world and utilizes packages like AMCL and the Navigation Stack.

Exploring, adding, and tuning specific parameters corresponding to each package to achieve the best possible localization results.

Note: Similar to project 1, you are required to document the work along the way. Use the project rubric as reference when you work through the project!

This project was done with native ROS installation . 

Native Installation or Virtual Machine
If you are working with a native ROS installation or from Term-1’s VM, some of the following package installation instructions might be required, if they aren't installed already -

$ sudo apt-get install ros-kinetic-navigation
$ sudo apt-get install ros-kinetic-map-server
$ sudo apt-get install ros-kinetic-move-base
$ rospack profile
$ sudo apt-get install ros-kinetic-amcl
