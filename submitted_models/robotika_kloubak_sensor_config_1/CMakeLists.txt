cmake_minimum_required(VERSION 2.8.3)
project(robotika_kloubak_sensor_config_1)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY launch materials meshes urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})

install(FILES model.sdf model.config
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})

