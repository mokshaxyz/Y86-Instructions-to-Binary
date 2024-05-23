# Y86 Assembly to Binary Converter

This repository contains a C program that converts three Y86 assembly instructions (HLT, NOP, RRMOVL) to their binary representation. The program reads from standard input and writes to standard output, with errors reported on standard error.

## Contents

1. Source files of the conversion program (`my_copy.c`)
2. A set of assembly programs designed for input to this converter
3. A log of all errors encountered during the development of the program

## Usage

### Compilation

To compile the program, run the following command:
gcc -o flame_cp my_copy.c

Running the Program

To run the program and copy files, use the following syntax:
./flame_cp -i <source file pathname> -o <destination file pathname>
You can specify - for either the source or destination to use standard input or output respectively.

Error Handling
The program detects and returns errors as positive integer exit codes. To display suitable error messages based on these codes, use the included Bash script:

Assembly Programs
A set of assembly programs designed to test the converter is included in the assembly_programs directory. These programs can be used to stress test the conversion process.
