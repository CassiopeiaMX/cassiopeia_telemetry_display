cmake_minimum_required(VERSION 2.8.3)
project(cassiopeia_telemetry_display)

find_package(catkin REQUIRED COMPONENTS
  roscpp
  rospy
  geometry_msgs
  sensor_msgs
  std_msgs
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)
