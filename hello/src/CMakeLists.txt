add_library(hello
    SHARED
        hello.cpp
    )
target_include_directories(hello
    PUBLIC ${PROJECT_SOURCE_DIR}/include
    )
