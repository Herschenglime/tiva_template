# Used to install the cmake files for tiva_cmake
cmake_minimum_required(VERSION 3.12)
project(TivaCMakeFiles LANGUAGES NONE)


install(DIRECTORY TivaCMake
  DESTINATION share)

install(DIRECTORY TivaToolchain
  DESTINATION share)
