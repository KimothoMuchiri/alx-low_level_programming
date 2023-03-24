ISO C defines a syntax for declaring a function to take a variable number or type of arguments. (Such functions are referred to as varargs functions or variadic functions.) However, the language itself provides no mechanism for such functions to access their non-required arguments; instead, you use the variable arguments macros defined in stdarg.h.

This section describes how to declare variadic functions, how to write them, and how to call them properly.

Compatibility Note: Many older C dialects provide a similar, but incompatible, mechanism for defining functions with variable numbers of arguments, using varargs.h
0x10. C - Variadic functions

0-sum_them_all.c: a function that returns the sum of all its parameters

1-print_numbers.c : a function that prints numbers, followed by a new line

2-print_strings.c : a function that prints strings, followed by a new line

3-print_all.c : a function that prints anything
