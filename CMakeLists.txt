# This package has no tests
cmake_minimum_required(VERSION 2.8.3)
project(hsrb_common_config)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY params
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
  PATTERN ".svn" EXCLUDE
)
