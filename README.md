## BeetleBot dependencies
This repository contains a snapshot of the dependencies for the Host PC software for
the BeetleBot platform.

As each of the original repositories has a number of versions, I created this repo to allow
easy access to the ones which were compatible with the rest of the
[BeetleBot software](https://github.com/refmitchell/beetlebot_software).

**I did not write any of the software in this repository.** The main repositories for
each included package are linked below.

- [vision_opencv](https://github.com/ros-perception/vision_opencv)
- [turtlebot3](https://github.com/ROBOTIS-GIT/turtlebot3)
- [turtlebot3_msgs](https://github.com/ROBOTIS-GIT/turtlebot3_msgs)
- [turtlebot3_simulations](https://github.com/ROBOTIS-GIT/turtlebot3_simulations)
- [DynamixelSDK](https://github.com/ROBOTIS-GIT/DynamixelSDK)

### For use with the BeetleBot
On the Host PC (Ubuntu 20.04 with ROS Noetic installed):

```
$ cd ~/catkin_ws/src
$ git clone https://github.com/refmitchell/beetlebot_dependencies
$ cd ~/catkin_ws
$ catkin_make
```