cmake_minimum_required(VERSION 2.8)

project(education)

set(SOURSE_EXE main.cpp)

include_directories(lib1)

add_executable(main ${SOURSE_EXE})

add_subdirectory(lib1)

target_link_libraries(main lib1)