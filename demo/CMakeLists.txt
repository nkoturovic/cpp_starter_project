add_executable(demo_use_mylib use_mylib.cpp)
target_link_libraries(demo_use_mylib
    PRIVATE project_options project_warnings mylib)
