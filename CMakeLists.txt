cmake_minimum_required(VERSION 3.3)
project(numerical_weather_prediction)

file(GLOB all_files "*.c")
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY "${CMAKE_CURRENT_SOURCE_DIR}/bin")

SET(SOURCE_FILES newton.c)

ADD_EXECUTABLE(${PROJECT_NAME} ${SOURCE_FILES})
