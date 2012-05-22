add_executable(qtvm main.cpp)
target_link_libraries(qtvm m) #link the math library

# just lib
#add_library(geometry geometry.cpp)

add_subdirectory(test)
