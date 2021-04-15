add_executable(prog_myprog main.cpp)
target_link_libraries(prog_myprog
    PRIVATE project_options project_warnings ${CONAN_LIBS} mylib)
