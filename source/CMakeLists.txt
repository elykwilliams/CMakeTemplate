
add_library(    
    Hello 
)

target_sources(
    Hello
PUBLIC
    helloworld.cpp
)

target_include_directories(
    Hello
INTERFACE
    ${CMAKE_SOURCE_DIR}/include
PRIVATE
    ${CMAKE_SOURCE_DIR}/source
)