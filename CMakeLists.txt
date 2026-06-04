cmake_minimum_required(VERSION 3.20)

project(your-mod-name)

find_package(Geode REQUIRED)

geode_add_mod()

target_sources(${PROJECT_NAME} PRIVATE
    src/main.cpp
)
