# C++ Project Template
Basic C++ project template packed with CMakeLists and Google Test framework. This repository served as the base setup for C++ project development.

To use this repository, update the following line CMakeLists.txt in the repository root.
```
project(CPP_TEMPLATE)
```
Replace CPP_TEMPLATE with the project name.

External library:
1. Google Test framework version **1.10.0**

Tested toolsets on Windows 10:
1. CMake version **3.16.0-rc1**
2. clang version **9.0.0**
3. ninja version **1.9.0**

To build and run:
1. cmake -GNinja -s . -t build
2. cd build
3. ninja
4. tests\runUnitTests
