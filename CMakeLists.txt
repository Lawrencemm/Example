# CMakeLists.txt
cmake_minimum_required(VERSION 3.10)
project(Example)

set(CMAKE_CXX_STANDARD 17)

add_executable(Example Example.cpp)

find_package(presentation REQUIRED)

target_link_libraries(Example presentation::presentation)
