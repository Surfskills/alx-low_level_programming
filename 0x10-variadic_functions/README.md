Variadic functions: stdarg, va_start, va_arg, va_end

0-sum_them_all.c - 
C function that returns the sum of all its parameters.

    Prototype: int sum_them_all(const unsigned int n, ...);
    If n == 0, return 0

1-print_numbers.c - 
C function that prints numbers, followed by a new line.

    Prototype: void print_numbers(const char *separator, const unsigned int n, ...);
    where separator is the string to be printed between numbers
    and n is the number of integers passed to the function
    If separator is NULL, doesn't print
    Prints a line at the end of thenction

2-print_strings.c - 
C function that prints strings, followed by a new line.

    Prototype: void print_strings(const char *separator, const unsigned int n, ...);
    where separator is the string to be printed between the strings
    and n is the number of strings passed to the function
    If separator is NULL, don’t print it
    If one of the string is NULL, print (nil) instead
    Prints  new line at the end of your function
    
3-print_all.c
C function that prints anything.

    Prototype: void print_all(const char * const format, ...);
    where format is a list of types of arguments passed to the function
        c: char
        i: integer
        f: float
        s: char * (if the string is NULL, print (nil) instead
        
        
