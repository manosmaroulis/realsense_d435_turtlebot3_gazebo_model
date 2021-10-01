cmake_minimum_required(VERSION 3.0.2)
project(realsense_d435_turtlebot3_gazebo_model)

find_package(catkin REQUIRED COMPONENTS
    )

# RealSense description
catkin_package()


install(DIRECTORY include/${PROJECT_NAME}/
  DESTINATION ${CATKIN_PACKAGE_INCLUDE_DESTINATION}
)

# Install files
install(DIRECTORY launch urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})


