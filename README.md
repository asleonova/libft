# libft

This project is an attempt to recode C standard functions (libc). As you might know, this is the first project 42 students have to do. 
Here is my approach at this problem.

## Usage:
* first run `make` or `make bonus` to create the library 
*(bonus rule creates the library with linked lists functions)*

* then `#include libft.h` in your .c files where you use these libft functions.

* then compile your .c files with the library using following flags:
`gcc -L. -lft *.c && ./a.out` \
_"*.c" - it's all your .c files_
