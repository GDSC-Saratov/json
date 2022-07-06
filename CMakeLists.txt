cmake_minimum_required(VERSION 3.23)
project (JSONParser)
set (CMAKE_CXX_STANDARD 11)

add_library (JSON INTERFACE)
target_include_directories (JSON INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/include)
