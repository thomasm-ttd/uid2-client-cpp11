﻿cmake_minimum_required (VERSION 3.12)

project ("uid2-client")

set (CMAKE_CXX_STANDARD 11)

add_subdirectory(lib)

add_subdirectory(app)

enable_testing()
add_subdirectory(test)
