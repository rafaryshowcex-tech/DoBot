cmake_minimum_required(VERSION 3.21)

project(DoBot)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

include($ENV{GEODE_SDK}/cmake/Geode.cmake)

add_subdirectory(src)
