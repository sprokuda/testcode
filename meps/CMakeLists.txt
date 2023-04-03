# CMakeList.txt : CMake project for CMakeProject1, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

# Add source to this project's executable.
add_executable (meps "main.cpp" "main.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET meps PROPERTY CXX_STANDARD 14)
endif()

# TODO: Add tests and install targets if needed.
