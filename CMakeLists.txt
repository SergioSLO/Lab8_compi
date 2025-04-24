cmake_minimum_required(VERSION 3.28)
project(lab8)

set(CMAKE_CXX_STANDARD 14)

include_directories(Lab8)

add_executable(lab8
        Lab8/exp.cpp
        Lab8/exp.h
        Lab8/main.cpp
        Lab8/parser.cpp
        Lab8/parser.h
        Lab8/scanner.cpp
        Lab8/scanner.h
        Lab8/token.cpp
        Lab8/token.h
        Lab8/visitor.cpp
        Lab8/visitor.h)
