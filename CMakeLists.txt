cmake_minimum_required(VERSION 3.0.0)
project(syscalls_linux VERSION 0.1.0 LANGUAGES C CXX)

file(GLOB SYSCALL "*")

add_executable(syscalls_linux ${REMOTE_SYSCALL})

