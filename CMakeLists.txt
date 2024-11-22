cmake_minimum_required(VERSION 3.22)
project(r2d2_servo)

find_package(ament_cmake REQUIRED)

ament_package()

install(DIRECTORY config launch rviz DESTINATION share/${PROJECT_NAME})
