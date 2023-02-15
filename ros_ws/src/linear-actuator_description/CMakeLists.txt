cmake_minimum_required(VERSION 2.8.3)
project(linear-actuator_description)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY files
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})

install(DIRECTORY images
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})

install(DIRECTORY urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
