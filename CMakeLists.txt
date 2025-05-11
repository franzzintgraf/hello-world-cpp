# Minimum CMake version required
cmake_minimum_required(VERSION 3.10)

# Project name
project(HelloWorld VERSION 1.0 LANGUAGES CXX)

# Set the C++ standard to use
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Add executable target
add_executable(hello-world ${PROJECT_SOURCE_DIR}/src/main.cpp)
