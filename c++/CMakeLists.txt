cmake_minimum_required(VERSION 2.8.11)
project(COMMAND_PATTERN)

set(SRCS src/main.cpp)
#use C++11
set_source_files_properties(${SRCS} PROPERTIES COMPILE_FLAGS -std=c++0x)

#create the executable 
add_executable(command_pattern ${SRCS})
