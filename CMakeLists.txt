cmake_minimum_required(VERSION 3.9)
project(c_learn)

set(CMAKE_CXX_STANDARD 11)

add_executable(c_learn
        main.c lib/sq_list.c lib/sq_list.h)
