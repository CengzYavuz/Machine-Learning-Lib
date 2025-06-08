cmake_minimum_required(VERSION 3.29)
project(MachineLearning)

set(CMAKE_CXX_STANDARD 20)

add_library(MachineLearning STATIC src/ML.cpp)
include_directories(${CMAKE_SOURCE_DIR}/include)
