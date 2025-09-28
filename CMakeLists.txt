cmake_minimum_required(VERSION 3.28)

project(libcanard)

add_library(${PROJECT_NAME} STATIC
    "libcanard/canard.c"
)

target_include_directories(${PROJECT_NAME}
    PUBLIC
        "libcanard"
)
