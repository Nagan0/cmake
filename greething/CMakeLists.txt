cmake_minimum_required(VERSION 3.0.0)

project(greething CXX)

add_executable(greething 
    src/main.cpp
    src/hello.cpp
    src/good_morning.cpp
    )
target_include_directories(greething
    PUBLIC ${PROJECT_SOURCE_DIR}/include
    )

