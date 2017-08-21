cmake_minimum_required(VERSION 2.8.3)
project(rosgo_messages)

find_package(catkin REQUIRED COMPONENTS gengo)

catkin_package()

rosgo_generate_messages(
  actionlib_msgs
  diagnostic_msgs
  geometry_msgs
  nav_msgs
  rosgraph_msgs
  sensor_msgs
  shape_msgs
  std_msgs
  std_srvs
  stereo_msgs
  tf2_msgs
  trajectory_msgs
  visualization_msgs
)

