# ENPM662 project implementation of a robot car using ROS

Contains all meshes, URDFs, xacro files, ros launch and config files for simulating and controlling the robot using gazebo and visualizing it in Rviz.

### Instructions to run:

1. Copy the folder assem3 in your catkin_ws/src folder.
2. cd ~/catkin_ws
3. catkin_make
4. source devel/setup.bash or ~/.bashrc
5. roslaunch assem3 gazebo.launch
6. Open rviz in another terminal and add robot model with frame set as base_link
