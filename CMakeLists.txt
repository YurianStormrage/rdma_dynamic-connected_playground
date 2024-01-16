# cmake version of server s51-s53 
cmake_minimum_required(VERSION 3.16)

# info
set (PACKAGE_NAME       "dc-demo")
set (PACKAGE_VERSION    "0.1")
set (PACKAGE_STRING     "${PACKAGE_NAME} ${PACKAGE_VERSION}")

project (${PACKAGE_NAME} VERSION ${PACKAGE_VERSION} LANGUAGES CXX)

# clangd
set (CMAKE_EXPORT_COMPILE_COMMANDS ON)

# Compile options
set (CMAKE_CXX_STANDARD 20)
set (CMAKE_CXX_STANDARD_REQUIRED ON)

