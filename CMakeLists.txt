cmake_minimum_required(VERSION 3.10)

project (Crush VERSION 1.0)

set(CMAKE_C_STANDARD )
set(CMAKE_C_STANDARD_REQUIRED True)

set(SOURCES 
    src/main.c
)

add_executable(Crush ${SOURCES})

target_include_directories(Crush PUBLIC include)
message(("Build Completed!"))