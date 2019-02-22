cmake_minimum_required(VERSION 3.12)
project(HashTable)

set(CMAKE_CXX_STANDARD 11)

add_executable(HashTable main.cpp HashTable.h GroupContainer.h Container.h Mem.h MemoryManager.h)