cmake_minimum_required(VERSION 3.5)

include($ENV{IDF_PATH}/tools/cmake/project.cmake)

get_filename_component(CMAKE_PROJECT_NAME "${CMAKE_CURRENT_SOURCE_DIR}" NAME)
project(${CMAKE_PROJECT_NAME})
