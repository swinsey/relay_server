cmake_minimum_required(VERSION 3.1)
project(relay_server)
set (CMAKE_CXX_STANDARD 11)
#SET(CMAKE_ARCHIVE_OUTPUT_DIRECTORY "${PROJECT_BINARY_DIR}")
#SET(CMAKE_LIBRARY_OUTPUT_DIRECTORY "${PROJECT_BINARY_DIR}")
#SET(CMAKE_RUNTIME_OUTPUT_DIRECTORY "${PROJECT_BINARY_DIR}")

ADD_SUBDIRECTORY(simple_uv)
ADD_SUBDIRECTORY(relay_server_sdk)
ADD_SUBDIRECTORY(relay_server_main)
