cmake_minimum_required(VERSION 3.5)

project(01.hello_world)

add_executable(hello_world 
    example.cpp
    hello_world.cpp
    move_me_out.cpp
)

set_target_properties(hello_world PROPERTIES
    CXX_STANDARD 17
    CXX_STANDARD_REQUIRED ON
)
