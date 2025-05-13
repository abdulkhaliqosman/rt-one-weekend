cmake_minimum_required(VERSION 3.10.0)
project(rt-one-weekend VERSION 0.1.0 LANGUAGES C CXX)

add_executable(rt-one-weekend main.cpp)
target_compile_features(rt-one-weekend PUBLIC cxx_std_17)

