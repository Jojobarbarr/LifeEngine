# add the executable target named LifeEngine
add_executable(LifeEngine main.cpp)
target_link_libraries(LifeEngine PRIVATE basic)

# add binary tree to the list of paths to search for include
# target_include_directories(LifeEngine PUBLIC "${PROJECT_BINARY_DIR}")