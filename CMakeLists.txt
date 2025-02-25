cmake_minimum_required(VERSION 3.14)

project(grpc_cpp_example)

# Set C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(SOURCES
  grpc-cpp-example/src/main.cpp
)

add_executable(${PROJECT_NAME} ${SOURCES})
