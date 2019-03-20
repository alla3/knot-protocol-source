cmake_minimum_required(VERSION 3.8.2)

project(proto)

FILE(GLOB app_sources src/*.c)
target_sources(app PRIVATE ${app_sources})
