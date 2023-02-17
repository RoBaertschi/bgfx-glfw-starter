# CMakeList.txt : CMake project for bgfx-glfw-starter, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("bgfx-glfw-starter")

# Add source to this project's executable.
add_executable (bgfx-glfw-starter "bgfx-glfw-starter.cpp" "bgfx-glfw-starter.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET bgfx-glfw-starter PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
