cmake_minimum_required(VERSION 3.2 FATAL_ERROR)
project(lastz)

set(ENV{LASTZ_INSTALL} ${CMAKE_BINARY_DIR}/bin)

execute_process (COMMAND make)
execute_process (COMMAND make install)
