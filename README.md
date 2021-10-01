# realsense_d435_turtlebot3_gazebo_model
A ready to use package, to simulate turtlebot waffle_pi with Intel RealSense D435 RGB-D camera.
In order for the package to work you need to install the following.

1)turtlebo3_description: 

          sudo apt-get install ros-${ROS_DISTRO}-turtlebot3-description

2)realsense2_description:

          sudo apt-get install ros-${ROS_DISTRO}-realsense2-description

3)Gazebo ros : 
          
          sudo sudo apt-get install ros-${ROS_DISTRO}-gazebo-ros

4)Gazebo plugins: 
          
         sudo apt-get install ros-${ROS_DISTRO}-gazebo-plugins

5)robot state publisher in order to have tf available in ros: 
         
         sudo apt-get install ros-${ROS_DISTRO}-robot-state-publisher


Build your workspace.


To launch the model type:

        roslaunch realsense_d435_turtlebot3_gazebo_model turtlebot3_world.launch

![waffle_pi_d435](https://user-images.githubusercontent.com/68281160/135662935-ce353523-cbe8-4ae6-b18a-2342bd8c304f.png)


