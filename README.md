# CSE-571-Artificial-Intelligence-Project

Follow the below specified steps in order to install the dependencies required to setup PR2 simulation.

      git clone https://github.com/PR2/pr2_simulator.git
      rosdep install pr2_gazebo
      rosmake pr2_gazebo
      sudo apt-get install ros-kinetic-pr2-teleop
      rosmake pr2_teleop
      
Sample run:

      roslaunch gazebo_ros empty_world.launch
      roslaunch pr2_gazebo pr2.launch
      roslaunch pr2_teleop teleop_keyboard.launch
      
To launch PR2 in turtlebot house environment, use the following commands:
      
      roslaunch pr2_gazebo pr2_turtlebot3_house.launch
      roslaunch pr2_gazebo pr2.launch
      roslaunch pr2_teleop teleop_keyboard.launch
