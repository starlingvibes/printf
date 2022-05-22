## \_printf()

This function named "\_printf()" imitates the actual "printf()" command located in the stdio.h library of C programming Language. It contains some of the basic features and functions found in the manual 3 of "printf".

\_printf() is a function that performs formatted output conversion and print data. Its prototype is the following:

      int _printf(const char *format, ...)

Where **format** contains the string that is printed.

\_printf() is a variadic function, it can receives n arguments that replace by n tags written inside the string.

The format tags prototype is the following:

    %[flags][length]specifier

If the program runs successfully, the **return value** is the amount of chars printed.

## File Functions

---

### \_printf.c

Own Printf Function That Performs Formatted Output Conversion And Print Data.

### holberton.h

Header File Where All Prototypes Are Saved.

### get_print_func.c

Pointer To A Function That Selects The Correct Function To Perform The Operation.

### print_buf.c

Function That Prints The Buffer.

### handl_buf.c

Function That Concatenates The Buffer Characters.

### print_chr.c

Function That Writes The Character C To Stdout.

/_ Indetifier : %c _/

### print_str.c

Function That Writes The String To Stdout.

/_ Indetifier : %s _/

### print_int.c

Function That Prints An Integer.

/_ Indetifier : %i or %d _/

### print_bnr.c

Function That Prints Decimal In Binary.

/_ Indetifier : %b _/

### print_oct.c

Function That Prints Decimal In Octal.

/_ Indetifier : %o _/

### print_hex.c

Function That Prints Decimal In Hexadecimal.

/_ Indetifier : %x _/

### print_upx.c

Function That Prints Decimal In Uppercase Hexadecimal.

/_ Indetifier : %X _/

### print_usr.c

Function That Prints A String And Values Of Non-Printed Chars.

/_ Indetifier : %S _/

### print_unt.c

Function That Prints An Unsigned Integer.

/_ Indetifier : %u _/

### print_rev.c

Function That Writes The String To Stdout In Reverse.

/_ Indetifier : %r _/

### print_rot.c

Function That Writes The String To Stdout In Rot13.

/_ Indetifier : %R _/

### print_add.c

Function That Prints The Address Of An Input Variable.

/_ Indetifier : %p _/

### print_long_oct.c

Function That Prints Long Decimal Number In Octal.

/_ Indetifier : %lo _/

### print_long_hex.c

Function That Prints Long Decimal Number In Hexadecimal.

/_ Indetifier : %lx _/

### print_long_int.c

Function That Prints A Long Integer.

/_ Indetifier : %li _/

### print_long_upx.c

Function That Prints A Long Decimal In Uppercase Hexadecimal.

/_ Indetifier : %lX _/

### print_long_unt.c

Function That Prints A Long Unsigned Integer.

/_ Indetifier : %lu _/

### print_short_oct.c

Function That Prints Short Decimal Number In Octal.

/_ Indetifier : %ho _/

### print_short_hex.c

Function That Prints Short Decimal Number In Hexadecimal.

/_ Indetifier : %hx _/

### print_short_int.c

Function That Prints A Short Integer.

/_ Indetifier : %hi _/

### print_short_upx.c

Function That Prints A Short Decimal In Uppercase Hexadecimal.

/_ Indetifier : %hX _/

### print_short_unt.c

Function That Prints A Short Unsigned Integer.

/_ Indetifier : %hu _/

### print_num_hex.c

Function That Print A Number In Hexadecimal Begining With 0 And x.

/_ Indetifier : %#x _/

### print_num_oct.c

Function That Prints A Number In Octal Begining With 0 And o.

/_ Indetifier : %#o _/

### print_num_upx.c

Function That Prints A Number In Uppercase Hexadecimal.

/_ Indetifier : %#X _/

### print_plus_int.c

Function That Prints An Integer With Plus Symbol.

/_ Indetifier : %+i _/

### print_space_int.c

Function That Prints An Integer Beginning With 0 And u.

/_ Indentifier : % i _/

### ev_print_func.c

Function That Returns The Amount Of Indentifiers.
