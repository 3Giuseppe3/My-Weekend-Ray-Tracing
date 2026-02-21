cmake_minimum_required(VERSION 3.10)

# Name of your project
project(InOneWeekend)

# Specify the C++ standard (Ray Tracing in One Weekend usually uses C++11 or higher)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Create the executable "inOneWeekend" from your main source file
# Note: Ensure "main.cpp" matches whatever you named your file!
add_executable(inOneWeekend src/main.cpp)
