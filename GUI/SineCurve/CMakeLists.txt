cmake_minimum_required(VERSION 3.0)
project(GUI_SineCurve)
set(CMAKE_CXX_COMPILER g++)
set(SOURCES src/hello.cc)
set(CMAKE_BUILD_TYPE Release)
add_executable(${PROJECT_NAME} ${SOURCES})