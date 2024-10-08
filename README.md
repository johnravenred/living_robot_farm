This repo is a virtual robot of Living_lab_robot. 

To clone this repo you'll need a ROS2 Humble

To install ROS2 Humble in Ubuntu dist. follow these steps from this website:
https://docs.ros.org/en/humble/Installation/Alternatives/Ubuntu-Development-Setup.html

After installing ROS2 Humble, you'll need to clone this repo to your workspace /ros2_humble is your workspace if you follow the installation 
$ cd ros_humble/src 
$ git clone git@github.com:johnravenred/living_robot_farm.git

return to your workspace file
$ cd ..
$ colcon build --symlink-install

then to run the virtual robot
$ ros2 launch living_robot_farm launch_sim.launch1.py

to move the robot you'll need to run teleop operation
$ ros2 run teleop_twist_keyboard teleop_twist_keyboard


