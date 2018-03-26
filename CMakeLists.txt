project(test)

add_library(A STATIC src/myFunction.cpp)

add_executable(output src/main.cpp)
target_link_libraries(output A)
