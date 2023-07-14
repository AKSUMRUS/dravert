cmake_minimum_required(VERSION 3.23)
project(dravert)

set(CMAKE_CXX_STANDARD 17)

add_executable(dravert dravert.cpp)

#clang++ -g -O3 dravert.cpp `llvm-config --cxxflags --ldflags --system-libs --libs core` -o dravert

