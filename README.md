# Build_Manipulator
How to build gazebo manipulators from the very beginning
## Install Ununtu on Jetson TX2
1. ```cd NVIDIA-INSTALLER```
2. ```sudo ./installer.sh```

The initial password of the Jetson TX2 is **nvidia**.
## Install ROS and catkin workspace.
1. Follow the links below.  
http://wiki.ros.org/kinetic/Installation/Ubuntu
http://wiki.ros.org/ROS/Tutorials/InstallingandConfiguringROSEnvironment
2. Install ROS packages.  
```sudo apt-get install ros-kinetic-ros-control* ros-kinetic-gazebo-ros*```

## Install Panda ROS packages
1. ```sudo apt install ros-kinetic-libfranka ros-kinetic-franka-ros```
2.
```
cd ~/catkin_ws
git clone https://github.com/mkrizmancic/franka_gazebo.git
catkin make
```


