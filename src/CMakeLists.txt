add_executable(MyExecutableFromSrc main.cpp)
target_link_libraries(MyExecutableFromSrc 
    PRIVATE project_options project_warnings ${CONAN_LIBS})
