cmake_minimum_required(VERSION 3.24)
project(IteratedList)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(IteratedList
        App.cpp
        ExtendedTest.cpp
        ExtendedTest.h
        ListIterator.cpp
        ListIterator.h
        IteratedList.cpp
        IteratedList.h
        ShortTest.cpp
        ShortTest.h)
