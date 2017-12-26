cmake_minimum_required(VERSION 3.8)
project(ThreadPool)

set(CMAKE_CXX_STANDARD 14)

set(EXAMPLE_SOURCE_FILES
        example.cpp)

set(CONTEXT_EXAMPLE_SOURCE_FILES
        context_example.cpp)

add_executable(example ${EXAMPLE_SOURCE_FILES})

add_executable(context_example ${CONTEXT_EXAMPLE_SOURCE_FILES})
