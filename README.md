![HolbertonSchool](https://www.holbertonschool.com/holberton-logo.png)

# Simple Shell

## Description

The hsh shell is a program that reads line by line from a file or the terminal line. It then interprets the lines and executes it if the line is a valid command.

## Usage

All the files are to be compiled on an Ubuntu 14.04 LTS machine with "gcc -Wall -Werror -Wextra -pedantic *.c -o hsh".

Once compiled, to start the program, run:
.br
$ ./hsh

To exit the program, run:
.br
hsh $ exit

## Built ins

The following built-ins are supported by the hsh shell:

.B env -
Print the current environment.

.B setenv VARIABLE VALUE -
Initialize a new environment variable, or modify an existing one.

.B unsetenv VARIABLE -
Remove an environment variable.

## Return

hsh shell will exit with status 0 unless status is specified.


## Author

[Andres Sepulveda](https://github.com/andi-s0106)
