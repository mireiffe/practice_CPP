cmake_minimum_required(VERSION 3.0)
project(hello_eigen)
set(CMAKE_CXX_COMPILER g++)
set(SOURCES src/test.cc)
set(CMAKE_BUILD_TYPE Release)
add_executable(${PROJECT_NAME} ${SOURCES}) 