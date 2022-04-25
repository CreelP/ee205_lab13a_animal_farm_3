cmake_minimum_required(VERSION 3.22)
project(ee205_lab13a_animal_farm_3)

set(CMAKE_CXX_STANDARD 14)

add_executable(ee205_lab13a_animal_farm_3 main.cpp Animal.cpp Animal.h Cat.cpp Cat.h Color.h config.h Gender.h List.cpp List.h Mammal.cpp Mammal.h Node.h SinglyLinkedList.cpp SinglyLinkedList.h Weight.cpp Weight.h)
