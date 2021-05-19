cmake_minimum_required(VERSION 2.8)

project(lib1)

set(SOURSE_LIB lib1.cpp)

add_library(lib1 STATIC ${SOURSE_LIB})