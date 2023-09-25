Instructions to use the package launch files to view the robot description

First in terminal, make sure to configure ROS with the command $ source /opt/ros/<ros-version>/setup.bash

Then change into directory lab2_ws and use the command $ source devel/setup.bash to configure the work space 

Also, make sure to start roscore

To open the robot description in rviz and also open the joint_state_publisher GUI, run the command $ roslaunch navvis_description display.launch use_xacro:=true 

The joint_state_publisher GUI allows you to control the wheel transformations

To open the robot description in rviz without the joint_state_publisher GUI, run the command $ roslaunch navvis_description display.launch use_xacro:=true use_joint_state_publisher_gui:=false