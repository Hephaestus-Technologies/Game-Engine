cmake_minimum_required(VERSION 3.5)
project(OpenGE)

add_subdirectory(OpenGE.Core)
include_directories(OpenGE.Core/include)

add_subdirectory(OpenGE.Core.UnitTests)