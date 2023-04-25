Title: C - printf Group Projects

The function _printf() is used to produce formatted output conversion, with the output being written to the standard output stream (stdout). The output is controlled by a format string that specifies how subsequent arguments are converted for output.

The format string is a character string composed of zero or more directives, which are ordinary characters copied unchanged to the output stream, and conversion specifications, each of which fetches zero or more subsequent arguments. Conversion specifiers are introduced by the character % and end with a conversion specifier.

The conversion specifiers include d and i for signed decimal notation, c for a char, s for a string, and %% for a literal %.

Functions used in the project include _write(), _print_a_char(), _print_a_string(), _print_a_integer(), _print_format(), _print_spec(), _print_invalid_spec(), _recursion_integer(), and _validate_char().

Upon successful return, _printf() returns the number of characters printed (excluding the null byte used to end output to strings). If an output error occurs, a negative value is returned.

The authors of _printf() are khalil ben and youssef frahat
