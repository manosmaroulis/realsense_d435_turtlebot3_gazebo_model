# realsense_d435_turtlebot3_gazebo_model
A ready to use package, to simulate turtlebot waffle_pi with Intel RealSense D435 RGB-D camera in Gazebo and ROS .
In order for the package to work you need to install the following.

* turtlebo3_description: 

          sudo apt-get install ros-${ROS_DISTRO}-turtlebot3-description

* realsense2_description:

          sudo apt-get install ros-${ROS_DISTRO}-realsense2-description

* Gazebo ros : 
          
          sudo sudo apt-get install ros-${ROS_DISTRO}-gazebo-ros

* Gazebo plugins: 
          
         sudo apt-get install ros-${ROS_DISTRO}-gazebo-plugins

* robot state publisher in order to have tf available in ros: 
         
         sudo apt-get install ros-${ROS_DISTRO}-robot-state-publisher


Clone the realsense plugin repository from pal-robotics (https://github.com/pal-robotics/realsense_gazebo_plugin) into your catkin_workspace/src folder

        git clone https://github.com/pal-robotics/realsense_gazebo_plugin.git

Build your workspace.


To launch the model type:

        roslaunch realsense_d435_turtlebot3_gazebo_model turtlebot3_world.launch

![waffle_pi_d435](https://user-images.githubusercontent.com/68281160/135662935-ce353523-cbe8-4ae6-b18a-2342bd8c304f.png)


