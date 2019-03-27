# Build_Manipulator
How to build gazebo manipulators from the very beginning
## Install ROS and catkin workspace.
1. Follow the links below.  
http://wiki.ros.org/kinetic/Installation/Ubuntu
http://wiki.ros.org/ROS/Tutorials/InstallingandConfiguringROSEnvironment
2. Install ROS packages.  
```sudo apt-get install ros-kinetic-ros-control* ros-kinetic-gazebo-ros*```

## Install Franka ROS packages
```sudo apt install ros-kinetic-libfranka ros-kinetic-franka-ros```

## Install a Franka gazebo package
```
cd ~/catkin_ws
git clone https://github.com/mkrizmancic/franka_gazebo.git
catkin make
```

## How to run Franka gazebo launch file
1. ```roslaunch gazebo_ros empty_world.launch```
2. Open new terminal and type ```roslaunch franka_gazebo panda_arm_hand.launch```

## Install Baxter packages
```
cd ~/catkin_ws
git clone https://github.com/RethinkRobotics/baxter_simulator.git
catkin_make
```


