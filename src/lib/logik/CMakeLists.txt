cmake_minimum_required (VERSION 3.8 FATAL_ERROR)

include_directories(${PROJECT_SOURCE_DIR}/src/lib)

file(GLOB SOURCES *.cpp core/*.cpp window/*.cpp)
add_library(logik ${SOURCES})
