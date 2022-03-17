cmake_minimum_required(VERSION 3.23.0)
project(HelloApp
        VERSION 0.0.1
        DESCRIPTION "Hello CPP Program"
        LANGUAGES CXX)
add_executable(HelloApp main.cpp)
target_compile_features(HelloApp PRIVATE cxx_std_11)