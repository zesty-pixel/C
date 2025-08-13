# The #include directive

C programs are divided into modules or functions. Some functions are written by users, like us, and many others are stored in the C library.

Library functions are grouped category-wise and stored in different files known as header files.

If we want to access the functions stored in the library, it is necessary to tell the compiler about the files to be accessed

This is achieved by using the preprocessor directive __#include__ as follows:
```c 
#include <filename>
```

_filename_ is the name of the library file that contains the required function definition. Preprocessor directives are placed at the beginning of a program.