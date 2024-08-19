# Starr

A C-Style programming language written with C++ 17, LLVM 18.1.8, Flex, and Bison.

![GitHub License](https://img.shields.io/github/license/RandomKiddo/Starr)
![Static Badge](https://img.shields.io/badge/C%2B%2B-17-blue?logo=cplusplus)
![Static Badge](https://img.shields.io/badge/LLVM-18.1.8-white?logo=llvm)

___

### Building and Running *Starr*

Starr uses CMake and a Makefile to build the project, meaning a version of GNU Make must be installed to build the executable. The project was initially made with `GNU Make 3.81`. 
Additionally, this project uses `Flex 2.6.4`, `GNU Bison 2.3`, `C++ 17`, `Clang 18.1.8`, and `LLVM 18.1.8`. 

First, clone the repository:
```shell
git clone https://github.com/RandomKiddo/Starr.git
```

Navigate to the `src` directory and clean it:
```shell
cd src
make clean
```

Then, make the program:
```shell
make
```

Finally, test the program using make:
```shell
make test
```

Or, in the `src` directory, run the parser executable:
```shell
./parser example.starr
```
___

### Syntax

```cpp
int do_math(int a) {
    int x = a % 5
    return x + 3        
}

echo(do_math(12))
```

___

<sub>This page was last updated on 08.19.2024</sub>