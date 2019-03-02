cmake_minimum_required(VERSION 3.13)
project(Example)

set(CMAKE_CXX_STANDARD 17)

add_executable(Example main.cpp)

find_package(presentation REQUIRED)

target_link_libraries(Example presentation::presentation)
