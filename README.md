# UIN-Campus

Systeme de gestion academique de l'Universite Islamique du Niger (projet fil rouge du cours de POO en C++ moderne).

## Environnement

- Systeme : Ubuntu
- Editeur : VS Code (extension clangd)
- g++ 15.2.0
- clang++ 21.1.8
- cmake 4.2.3
- ninja 1.13.2
- gdb 17.1
- git 2.53.0
- Norme : C++23

## Construction

    cmake --preset debug
    cmake --build --preset debug
    ./build/debug/uin-campus

## Qualite du code

    clang-format -i app/main.cpp src/version.cpp include/uincampus/version.hpp
    clang-tidy -p build/debug app/main.cpp src/version.cpp