cmake_minimum_required(VERSION 3.6)
project(Jzon)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES Jzon.cpp Jzon.h)

add_library(Jzon SHARED ${SOURCE_FILES})