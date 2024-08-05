# Task-3-ROS

1. Install the teleop_twist_keyboard Package
   

sudo apt install ros-foxy-teleop-twist-keyboard

3. Launch the Turtlesim Node
First, start the ROS 2 core in one terminal:



source /opt/ros/foxy/setup.bash
ros2 run turtlesim turtlesim_node


3. Run the Teleop Node
In another terminal, run the teleop node to control the turtle:


source /opt/ros/foxy/setup.bash
ros2 run teleop_twist_keyboard teleop_twist_keyboard


4. Control the Turtle
   
The teleop_twist_keyboard node will start, and you can control the turtle using the following keys:

i: move forward

k: stop

j: turn left

l: turn right

,: move backward

u: turn forward left

o: turn forward right

m: turn backward left

.: turn backward right

Using the teleop_twist_keyboard package simplifies the process, as it is a ready-made node for keyboard teleoperation, making it easier to control the turtle without writing any additional code.
