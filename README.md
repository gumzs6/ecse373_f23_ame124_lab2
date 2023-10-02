<h1>Navvis Description</h1>
<h2>Overview</h2>
<p>This package provides the navvis robot description and the way to view it in RVIZ.</p>
<h2>Instructions to use the package launch files to view the robot description</h2>
<ol>
  <li>Open terminal and configure ROS with the command $ source /opt/ros/< ros-version >/setup.bash</li>
  <li>Pull this package into ROS configured workspace</li>
  <li>Start roscore.</li>
  <li>To open the robot description in RVIZ and also open the joint_state_publisher GUI, run the command $ roslaunch navvis_description display.launch use_xacro:=true</li>
      <ul>
        <li>The argument use_xacro:=true uses the xacro file when RVIZ launches and use_xacro:=false uses the urdf file when RVIZ launches.</li>
        <li>The joint_state_publisher GUI allows you to control the wheel transformations and can be turned off with argument use_joint_state_publisher_gui:=false</li>
      </ul>
