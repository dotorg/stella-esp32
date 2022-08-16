# This file was automatically generated for projects
# without default 'CMakeLists.txt' file.

FILE(GLOB_RECURSE main_sources ${CMAKE_SOURCE_DIR}/main/*.*)
FILE(GLOB_RECURSE component_sources ${CMAKE_SOURCE_DIR}/components/*.*)

idf_component_register(SRCS ${main_sources} ${component_sources})
