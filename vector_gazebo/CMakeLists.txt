cmake_minimum_required(VERSION 3.0.2)
project(vector_gazebo)

find_package(catkin REQUIRED COMPONENTS
  gazebo_ros
  gazebo_ros_control
)

catkin_package()

