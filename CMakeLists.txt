cmake_minimum_required(VERSION 3.10)
project(baize-app)

set(CMAKE_CXX_STANDARD 17)

add_subdirectory(lib)

add_executable(main main.cpp)

target_link_libraries(main PRIVATE baize)

