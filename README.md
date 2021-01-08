# ROS-noetic-guide
some instructions to install ros noetic and pkgs 


## Installation guide

1 - Install ROS Noetic
(Ref: http://wiki.ros.org/noetic/Installation/Ubuntu) Just follow this :)

2 - Build the workspace
(Ref: http://wiki.ros.org/catkin/Tutorials/create_a_workspace)

`source /opt/ros/noetic/setup.bash`

`mkdir -p ~/my_ws/src`

`cd my_ws` 

First time with python3 must use: `catkin_make -DPYTHON_EXECUTABLE=/usr/bin/python3` to make the ws

`source devel/setup.bash`

`echo $ROS_PACKAGE_PATH`

3 - Ouster pkg
(Ref: https://github.com/ouster-lidar/ouster_example)

`sudo apt install build-essential cmake libglfw3-dev libglew-dev libeigen3-dev \
     libjsoncpp-dev libtclap-dev`
     
4 - Pylon pkg
(Ref: https://github.com/basler/pylon-ros-camera)

`sudo apt install python3-rosdep2`
`rosdep update`
