
# Gazebo Keyboard Control

This contains a simulation setup and manual control program for a simple Gazebo tankbot.
To change the velocity of the robot, hold down the corresponding key, and the Gazebo robot will follow that command.
The command keys are as setup as following:
+ **w**: Forward
+ **s**: Reverse
+ **a**: Veer Left
+ **d**: Veer right
+ **q**: Spin left
+ **e**: Spin right
+ **Space**: Stop
+ **~**: Exit program

This requires [Gazebo](http://gazebosim.org/) and is intended to work on a
(non-virtualized) Ubuntu 20.04 or Debian 10 system.

# Build & Run

Running `make` in the **brain** directory will create a `brain` executable. Spin up a gazebo world, and run the `brain` executable. If your cursor is focused in the terminal window that `brain` is running in, the brain program will read and interpret your keyboard commands.

***NOTE: Only tested on Ubuntu 20***

# References
- https://github.com/joselusl/aruco_gazebo [For Aruco Models]
- https://stackoverflow.com/questions/10344246/how-can-i-convert-a-cvmat-to-a-gray-scale-in-opencv
- https://docs.opencv.org/master/d5/dae/tutorial_aruco_detection.html [For Aruco Detection]
