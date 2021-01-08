# ROS-noetic-guide
some instructions to install ros noetic and pkgs 


## install guide

1 - INstall ROS Noetic
(Reference:) 

2 - Build the workspace
(Reference: http://wiki.ros.org/catkin/Tutorials/create_a_workspace)

`source /opt/ros/noetic/setup.bash`

`mkdir -p ~/my_ws/src`

`cd my_ws` 

First time with python3 must use: `catkin_make -DPYTHON_EXECUTABLE=/usr/bin/python3` to make the ws
`source devel/setup.bash`
`echo $ROS_PACKAGE_PATH`
