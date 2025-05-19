# C_stdlib
[![License](https://img.shields.io/badge/license-Unlicense-blue)](/LICENSE)

A reimplementation of selected C Standard Library functions, written in compliance with the 42 School’s Norm guidelines and restrictions.

## Table of Contents

- [About](#about)  
- [Features](#features)  
- [Usage](#usage)   

## About

`C_stdlib` is a custom implementation of 25+ functions from the C Standard Library (e.g. `ft_strlen`, `ft_memcpy`, `ft_strchr`).  
This project was part of the 42 School curriculum, where you must adhere to strict style and function-use restrictions to deepen your understanding of low-level C programming.

## Features

- Reimplements core libc functions: memory, string, character, and I/O helpers  
- 100% Norm-compliant: no forbidden functions, 25 lines max per function, 80-column limit  
- Thoroughly tested on edge cases (NULL pointers, zero lengths, etc.)

## Usage

1. Clone this repository
   ```bash
   git clone https://github.com/Madm4t/C-stdlib.git

2. Include the header in your program
   ```bash
   #include "libft.h"

3. When compilink your Program link the library, for example
   ```bash
   gcc -Wall -Werror -Wextra -I. main.c -L. -lft -o main
