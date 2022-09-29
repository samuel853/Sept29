cmake_minimum_required(VERSION 3.23)
project(Sept29)

set(CMAKE_CXX_STANDARD 14)

add_executable(Sept29 main.cpp QueueInterface.h ArrayQueue.h PrecondViolatedExcep.h)
