cmake_minimum_required(VERSION 3.0.2)
project(vector_control)

find_package(catkin REQUIRED COMPONENTS
  controller_manager
  interactive_marker_twist_server
  joint_state_controller
  teleop_twist_keyboard
)

catkin_package()
