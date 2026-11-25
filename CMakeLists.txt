#Минимально требуемая версия CMake
cmake_minimum_required(VERSION 3.16)

project(IndustrialControllerTesting LANGUAGES C) #Объявление проекта, его названия. Использовано ключевое слово для установки языка С.

set(CMAKE_C_STANDARD 11) #Установка стандарта языка С11

set(CMAKE_C_STANDARD_REQUIRED ON) #Команда устанавливает, что требуется именно данная версия языка С и не допускается применение его более старых версий.

add_executable(blink_mode src/blink_mode.c)

