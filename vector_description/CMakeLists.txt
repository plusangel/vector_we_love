cmake_minimum_required(VERSION 3.0.2)
project(vector_description)

find_package(catkin REQUIRED COMPONENTS
  rospy
  gazebo_ros
)

catkin_package(
CATKIN_DEPENDS rospy gazebo_ros
)


