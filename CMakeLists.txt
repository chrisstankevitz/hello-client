CMAKE_MINIMUM_REQUIRED(VERSION 2.8)

PROJECT(hello-client)

ADD_LIBRARY(hello UNKNOWN IMPORTED)

ADD_EXECUTABLE(hello-client hello-client.cpp)

TARGET_LINK_LIBRARIES(hello-client hello)
