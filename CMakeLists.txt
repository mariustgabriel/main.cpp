cmake_minimum_required(VERSION 3.20)
project(ConcertePOO)

set(CMAKE_CXX_STANDARD 23)

add_executable(ConcertePOO main.cpp)
target_include_directories(ConcertePOO PUBLIC include)