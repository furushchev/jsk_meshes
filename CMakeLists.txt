cmake_minimum_required(VERSION 2.8.3)
project(jsk_meshes)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY models worlds owl
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
  USE_SOURCE_PERMISSIONS)
