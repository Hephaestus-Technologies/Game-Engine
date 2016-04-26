cmake_minimum_required(VERSION 3.5)
project(OpenGE.Core.UnitTests)

add_subdirectory(GTest)
include_directories(${gtest_dir}/includes)