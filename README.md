# Rost-noetic-manipulation-turtlesim

### A window showing a turtle when running rosrun turtlesim turtlesim_node.
![image](https://github.com/hussein-ak/Ros-noetic-download-steps/assets/173874366/4fd746cf-e95c-48a5-8cfc-81419b5c8ef2)



### Update your package list:
sudo apt-get update

### Install the TurtleSim package:

sudo apt-get install ros-$(rosversion -d)-turtlesim

![image](https://github.com/user-attachments/assets/f0f5298e-c9e2-4c20-9618-0a41c78418fc)

### Launch the ROS core:
roscore

![image](https://github.com/user-attachments/assets/e34e3803-330b-4229-9487-dcfb7e36dc32)


### In a new terminal, run the TurtleSim node:

rosrun turtlesim turtlesim_node

![image](https://github.com/user-attachments/assets/ae86b098-821e-4e1e-87fd-a88e903967f7)

### In a new terminal, run the teleop node to control the turtle using the keyboard:

rosrun turtlesim turtle_teleop_key

![image](https://github.com/user-attachments/assets/7bb53549-389b-4c50-baa6-b31e06883f7c)



### This command displays the data being sent on the turtle1/pose topic. The results show the turtle's coordinates and velocity values as follows:

rostopic echo /turtle1/pose

![image](https://github.com/user-attachments/assets/d3c6b385-0b98-46dd-89a4-c9f9f175d2f0)





