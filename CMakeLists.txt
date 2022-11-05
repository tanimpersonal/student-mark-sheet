cmake_minimum_required(VERSION 3.23)
project(student_oop_practice)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(student_oop_practice
        student.cpp)

add_executable(student student.cpp)