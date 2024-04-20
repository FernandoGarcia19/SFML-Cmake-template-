# CMakeList.txt : CMake project for SFML-CMake-Template, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (SFML-CMake-Template "SFML-CMake-Template.cpp" "SFML-CMake-Template.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET SFML-CMake-Template PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
