cmake_minimum_required(VERSION 3.18)

enable_testing()
add_test(NAME 1-syntax_check
         COMMAND ${Python_EXECUTABLE} -m compileall ${PROJECT_SOURCE_DIR})
