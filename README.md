# Project 0x11 - C: printf

## Resources
Read or watch:
- [Secrets of printf](https://www.cypress.com/file/54761/download)
- [Group Projects concept page](https://intranet.hbtn.io/concepts/111)
- [Flowcharts concept page](https://intranet.hbtn.io/concepts/130)
- `man` or `help`: `printf (3)`

## Requirements
### General
- **Allowed editors:** vi, vim, emacs
- All your files will be compiled on Ubuntu 20.04 LTS using gcc, with the options `-Wall -Werror -Wextra -pedantic -std=gnu89`
- All your files should end with a new line
- A `README.md` file at the root of the project folder is mandatory
- Your code should use the Betty style. It will be checked using `betty-style.pl` and `betty-doc.pl`
- Do not use global variables
- No more than 5 functions per file
- In the following examples, the `main.c` files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own `main.c` files at compilation. Our `main.c` files might be different from the one shown in the examples
- The prototypes of all your functions should be included in your header file called `main.h`
- Don’t forget to push your header file
- All your header files should be include guarded
- Note that we will not provide the `_putchar` function for this project

## GitHub
- There should be one project repository per group. The other members do not fork the project to ensure only one of the team has the repository in their GitHub account; otherwise, you risk scoring 0%

## More Info
### Authorized functions and macros
- `write` (man 2 write)
- `malloc` (man 3 malloc)
- `free` (man 3 free)
- `va_start` (man 3 va_start)
- `va_end` (man 3 va_end)
- `va_copy` (man 3 va_copy)
- `va_arg` (man 3 va_arg)

### Compilation
Your code will be compiled this way:
```bash
$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c
