cmake_minimum_required(VERSION 3.0.2)

project(mytest CXX)

include(CheckCXXCompilerFlag)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -g -O0 -Wall -W")

include_directories(.)

add_subdirectory(mytest)
