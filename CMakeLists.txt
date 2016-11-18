cmake_minimum_required(VERSION 3.6)
project(MANAGING_LINUX_DAEMONS_CPP)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp)
add_executable(daemons ${SOURCE_FILES})