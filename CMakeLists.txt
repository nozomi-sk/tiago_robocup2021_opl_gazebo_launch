# This package has no tests
cmake_minimum_required(VERSION 2.8.3)
project(tiago_robocup2021_opl_gazebo_launch)
find_package(catkin REQUIRED)
catkin_package()

install(DIRECTORY launch/
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/launch
)
