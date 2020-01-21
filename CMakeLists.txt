cmake_minimum_required(VERSION 3.12)

project(main)

add_executable(main main.cpp)

#install(TARGETS main  DESTINATION bin)

enable_testing()
add_test(NAME main COMMAND main)