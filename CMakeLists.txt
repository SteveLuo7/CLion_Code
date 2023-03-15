cmake_minimum_required(VERSION 3.24)
project(CLion_Code)

set(CMAKE_CXX_STANDARD 17)

add_executable(CLion_Code main.cpp)

add_executable(cal cal.cpp)
add_executable(repeat repeat.cpp)
add_executable(main main.cpp)