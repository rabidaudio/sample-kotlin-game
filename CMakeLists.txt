cmake_minimum_required(VERSION 3.8)

set(CMAKE_MODULE_PATH ${CMAKE_CURRENT_LIST_DIR}/KotlinCMakeModule)

project(game Kotlin)

#cinterop(
#        NAME ncurses
#        DEF_FILE ncurses.def)

konanc_executable(
        NAME game
        SOURCES src/main.kt
        #LIBRARIES ncurses
)

#konanc_test(
#        NAME gameTest
#        SOURCES src/main.kt test/tests.kt
#        LIBRARIES ncurses)