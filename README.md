# ROS-Robot-Design-in-Gazebo
This repo contains a ROS based urdf file that's used for designing a simple differential drive  robot for visualization on the Gazebo Sim. 

OS:  Ubuntu Xenial 16.04 LTS, ROS: Kinetic

Download the Repo. Extract it and put the mcflurry_description folder into your workspace's src folder (eg: catkkin_ws/src)
Go out of the src folder into the workspace folder. Run catkin_make for building the files. 

Have a Roscore running. And open an Empty Gazebo sim (Gazebo 7 used here) in a different terminal. 

run roslaunch mcflurry_description spawn.launch. Have fun!
