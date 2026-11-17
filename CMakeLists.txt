cmake_minimum_required(VERSION 3.30)
project(gbafix)

include(GNUInstallDirs)

add_executable(gbafix gbafix.c)

install(TARGETS gbafix RUNTIME DESTINATION ${CMAKE_INSTALL_BINDIR})
