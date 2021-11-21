cmake_minimum_required(VERSION 3.0)

# version information is optional
project(simple VERSION 1.0.0)

include_directories(inc)

add_executable(simple.out src/main.cpp src/display.cpp)
