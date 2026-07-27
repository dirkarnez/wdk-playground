cmake_minimum_required(VERSION 3.15)

wdk_add_driver(simple KMDF 1.15
    simple.c
)

# target_include_directories(KmdfCppLib INTERFACE .)

# target_link_libraries(simple KmdfCppLib)
