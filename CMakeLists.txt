cmake_minimum_required(VERSION 3.12.0)
project(vteffect C CXX)
set(CMAKE_BUILD_TYPE Debug)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

add_subdirectory(stdout_control)
add_subdirectory(scat)
add_subdirectory(vtdump)
add_subdirectory(vteffect)
add_subdirectory(vtasm)

