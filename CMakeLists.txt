cmake_minimum_required(VERSION 3.15)
project(PankeyEngineBaseTests)

# Header-only library
add_library(PankeyEngineBaseTests INTERFACE)

# Expose the folder with headers
target_include_directories(PankeyEngineBaseTests INTERFACE
    ${CMAKE_CURRENT_SOURCE_DIR}   # headers are in the root of ThePankeyEngine-Base-Tests
)

