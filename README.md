***1_turtlesim Using ROS 1***

- Begin by sourcing the ROS setup script (/opt/ros/noetic/setup.bash for ROS Noetic) in the terminal to initialize the ROS command-line tools and environment variables.
bash
```ruby
source /opt/ros/noetic/setup.bash
```

- Start the ROS in another terminal using the command
```ruby
roscore
```

- i launched the Turtlesim simulator also in another terminal using 
```ruby
rosrun turtleism turtleism_node
```



<img src="https://github.com/DeemaEssam/turtlesim_Using_Ros1_And_ROs2/assets/106381596/559b750e-4044-403c-8f30-4ff449cf726a" width="350" height="250">

<img src="https://github.com/DeemaEssam/turtlesim_Using_Ros1_And_ROs2/assets/106381596/2786ee24-6193-4f19-b644-7d396a26f033" width="350" height="250">

<img src="https://github.com/DeemaEssam/turtlesim_Using_Ros1_And_ROs2/assets/106381596/de632460-a13f-48de-9a6f-cf7afb21169d" width="350" height="250">

<img src="https://github.com/DeemaEssam/turtlesim_Using_Ros1_And_ROs2/assets/106381596/05ed329f-c88e-4dac-afda-dc394abaa9d8" width="600" height="200">

****************************************************************************************************************************************************
***2_turtlesim Using ROS 2***

- ensuring that ROS 2 environment is properly set up in VirtualBox environment. This involves sourcing the ROS 2 setup script (/opt/ros/foxy/setup.bash) in every terminal session where i intend to work with ROS 2 commands. This step initializes the ROS 2 command-line tools (ros2, ros2run, etc.) and environment variables.
```ruby
source /opt/ros/foxy/setup.bash
```
- i launched the Turtlesim simulator using the turtlesim_node command. This starts the graphical interface where i can see and interact with a turtle.
```ruby
ros2 run turtlesim turtlesim_node
```
- enable keyboard control of the turtle in Turtlesim
```ruby
ros2 run turtleism turtle_teleop_key
```

<img src="https://github.com/DeemaEssam/turtlesim_Using_Ros1_And_ROs2/assets/106381596/6c21657e-0682-4482-ab19-197a83a22f5c" width="400" height="300">

<img src="https://github.com/DeemaEssam/turtlesim_Using_Ros1_And_ROs2/assets/106381596/38461377-7ee3-40c9-b595-33f3659ae1f4" width="400" height="300">
