cmake_minimum_required(VERSION 3.6)   # CMake version check
project(ICP)               # Create project "simple_example"
set(CMAKE_CXX_STANDARD 11)            # Enable c++11 standard

set(SOURCE_FILES group_ass_1.c)            # Add main.cpp file of project root directory as source file
add_executable(ICP ${SOURCE_FILES})       # Add executable target with source files listed in SOURCE_FILES variable