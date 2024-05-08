cmake_minimum_required(VERSION 3.16.0)
project(qualla LANGUAGES C CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_library(test STATIC test.cpp)
set_target_properties(test PROPERTIES POSITION_INDEPENDENT_CODE ON)
