cmake_minimum_required(VERSION 2.8)

project(lab_2)

add_library(calculator
    calculator.h
    calculator.cpp
)

add_executable(lab_2
  main.cpp
)

target_link_libraries(lab_2 calculator)
