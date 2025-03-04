README for the C - Hello, World Project
Project Overview

This project is focused on understanding the basics of the C programming language and exploring essential concepts such as compilation, preprocessing, and code generation. You will be required to write scripts and C programs that perform fundamental tasks in the C programming process, helping you become familiar with compiling and running C code in a Unix-like environment.

The project consists of tasks designed to help you gain a deeper understanding of C programming, including file preprocessing, compiling, assembly generation, and output handling.
Key Concepts Covered:

    The role of the C compiler and preprocessor
    Writing basic C programs using functions like puts, printf, and others
    Understanding the compilation process and file generation in C
    Working with assembly code and different machine architectures (Intel vs. GNU syntax)

Project Requirements

    Programming Language: C
    Allowed Editors: vi, vim, emacs
    Compiling Environment: Ubuntu 20.04 LTS, GCC compiler with options -Wall -Werror -Wextra -pedantic -std=gnu89
    Coding Style: Betty style, and the code must be linted using the Betty linter.
    Shell Scripts: The shell scripts should be exactly two lines long with a proper shebang (#!/bin/bash).

Tasks Overview

    Preprocessor:
        Create a script that runs a C file through the preprocessor and saves the result to a file.
        The C file name is stored in the environment variable $CFILE.

    Compiler:
        Write a script that compiles a C file but does not link it.
        The output file should be named <filename>.o (object file).

    Assembler:
        Generate assembly code from a C file and save it as a .s file.

    Name:
        Compile a C file into an executable named cisfun.

    Hello, puts:
        Write a C program that prints a specific message using puts without using printf.

    Hello, printf:
        Write a C program that prints a specific message using printf without using puts.

    Size is not grandeur, and territory does not make a nation:
        Write a C program to print the size of various data types on the system.

    Intel (Advanced):
        Generate assembly code in Intel syntax from a C file and save it to an output file.

Requirements for All Scripts

    All files should be compiled using gcc with the following options: -Wall -Werror -Wextra -pedantic -std=gnu89.
    Your code should be free of errors and warnings during compilation.
    Each C program must return 0 if it runs successfully.
    The shell scripts should be exactly two lines long.

Resources

To help you get started with C programming, refer to the following resources:

    Documentation:
        Everything you need to know to start with C.
        Dennis Ritchie and Brian Kernighan’s works on C programming.
        Learning resources on the compilation process and using tools like gcc, printf, puts, and putchar.

    C Tools:
        gcc: C compiler
        man: For manual pages on gcc, printf, and other functions

    Betty Style:
        You must follow the Betty coding style.
        Use the betty linter to check your code formatting.

Installation

You may need to install the following tools to run the scripts:

sudo apt-get install gcc libc6-dev-i386

To use the Betty linter:

sudo ./install.sh

GitHub Repository

    GitHub Repository: alx-low_level_programming
    Directory: 0x00-hello_world

Each task has its own script or C file, which you can check out in the respective directories.
Author

This project is part of the ALX program, aimed at developing software engineering skills in C programming.
