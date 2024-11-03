cmake_minimum_required(VERSION 3.28.3)

project(o1heap)

add_library(o1heap STATIC
    "o1heap/o1heap.c"
)

target_include_directories(o1heap
    PUBLIC
        "o1heap"
)
