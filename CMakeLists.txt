cmake_minimum_required(VERSION 3.2 FATAL_ERROR)

project(studing_cpp)

add_definitions("-Wno-c++11-extensions")

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)


#test
add_executable(test
    testing_path/main.cpp
)

#first lection ()
add_executable(lection1
    lections_cherepanov/semestr1/lection1/main.cpp
)