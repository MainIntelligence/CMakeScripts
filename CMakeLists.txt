cmake_minimum_required(VERSION 3.5)

project(CMakeScripts)

include_directories(${INCLUDE_DIRS})


#INSTALL
include(GNUInstallDirs)

install(DIRECTORY Scripts/
	DESTINATION ${CMAKE_INSTALL_BINDIR})

#TODO: Generate executable CMake utilities and install them in bin directory as well.
