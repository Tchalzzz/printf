This repository contains tasks that pertain to the custom implementation of the printf funcction found in the stdio.h library of C language. It is a joint project developed by Effiong Ekpe and Muhammad Abubakar, all of Cohort 9.

The printf function will handle the following coversion specifiers:
c
s
%
d
i
u
o
x
X
R
r
and length modifiers for non-custom conversion specifiers
Example:
_printf("Let's try to printf a simple sentence.\n");
_printf("String:[%s]\n", "I am a string !");
_printf("String:[%s]\n", "I am a string !");
_printf("Length:[%d, %i]\n", len, len);
_printf("Length:[%d, %i]\n", len2, len2);
    _printf("Negative:[%d]\n", -762534);
    printf("Negative:[%d]\n", -762534);
    _printf("Unsigned:[%u]\n", ui);
    printf("Unsigned:[%u]\n", ui);
    _printf("Unsigned octal:[%o]\n", ui);
    printf("Unsigned octal:[%o]\n", ui);
    _printf("Unsigned hexadecimal:[%x, %X]\n", ui, ui);
    printf("Unsigned hexadecimal:[%x, %X]\n", ui, ui);
    _printf("Character:[%c]\n", 'H');
    printf("Character:[%c]\n", 'H');
    _printf("String:[%s]\n", "I am a string !");
    _printf("String:[%s]\n", "I am a string !");
    _printf("Address:[%p]\n", addr);
    _printf("Address:[%p]\n", addr);
    _printf("Len:[%d]\n", len);
    _printf("Len:[%d]\n", len2);
    _printf("Unknown:[%r]\n");
    _printf("Unknown:[%r]\n");
