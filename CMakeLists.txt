cmake_minimum_required(VERSION 2.8)

project(Test_lib_2)

add_library(test_lib_2 test_lib_2.cpp)

install(TARGETS test_lib_2 DESTINATION lib)
install(FILES test_lib_2.h DESTINATION include)