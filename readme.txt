ompiler, since 9 is outside of octal’s 0 to 7 range. A more common base for
numbers used by programmers is hexadecimal, which matches cleanly with modulo
8 word sizes, such as 8, 16, 32, and 64 bits. You signify a hexadecimal constant with
a leading zero-x, (0x or 0X). The range of a hexadecimal digit is 0 to 15, so A
through F (or a through f) are substituted for 10 through 15.
Integer literals create an int value, which in Java is a 32-bit integer value. Since
Java is strongly typed, you might be wondering how