cmake_minimum_required(VERSION 3.0)

project(oop_exercise_01 VERSION 1.0.0 LANGUAGES CXX)

add_executable(oop_exercise_01 LR1.cpp)


install(TARGETS oop_exercise_01 DESTINATION bin)
set_target_properties(oop_exercise_01 PROPERTIES CXX_STANDART 14 CXX_STANDART_REQUIRED ON)
