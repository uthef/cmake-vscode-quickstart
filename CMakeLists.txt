cmake_minimum_required(VERSION 3.15)
project(cmake-vscode-quickstart)

include_directories(src)

add_executable(${PROJECT_NAME} 
    src/main.cpp
)

set_target_properties(${PROJECT_NAME} PROPERTIES OUTPUT_NAME out)
