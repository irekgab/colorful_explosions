cmake_minimum_required(VERSION 4.0)
project(colorful_explosions)

set(CMAKE_CXX_STANDARD 26)

include_directories(include)
link_directories(include)

add_executable(colorful_explosions main.cpp include/lodepng/lodepng.cpp)
