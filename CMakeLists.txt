cmake_minimum_required(VERSION 3.12)
project(LAnixMessagingQueues)

set(CMAKE_CXX_STANDARD 14)

set(SOURCE_FILES client.cpp client.h LaQueue.cpp lqueue.h PQueue.cpp PQueue.h README.md server.cpp server.h siginfo.h lqueue.cpp)

add_executable(LAnixMessagingQueues ${SOURCE_FILES})