# Указываем минимальную версию CMake, которую будем использовать
cmake_minimum_required(VERSION 3.31.7)

# Назовём проект
project(hello_world)

# Добавляем исполняемый файл, указывая исходные файлы
add_executable(hello main.cpp hello.cpp factorial.cpp)