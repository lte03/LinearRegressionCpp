cmake_minimum_required(VERSION 3.29)

project(SIMPLE_LR VERSION 1.0)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(outfile SimpleLinearRegression.h SimpleLinearRegression.cpp TestSimpleLinearRegression.cpp)
