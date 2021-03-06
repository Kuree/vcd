cmake_minimum_required(VERSION 3.8)
project(vcd)

set(CMAKE_CXX_STANDARD 17)

add_library(vcd src/vcd.cc)
target_include_directories(vcd PRIVATE include)
