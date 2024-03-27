The purpose of this assignment is to learn how to convert a floating-point number into
a hexadecimal (base 16) number.
Write a complete C++ program that will allow the user to convert a sequence of
floating-point numbers into hexadecimal numbers. The hexadecimal number must be
stored in a vector of characters.
System Requirements:
1. The main function will use a loop to do the following:
a. Input a floating-point number from the console screen.
b. Call a function entitled Float_To_Hex. This function will take a floatingpoint number in as a parameter.
The function will return a vector of characters. This vector will contain the
characters that make up the hex number.
Example: 757.25 => ‘2’,’F’,’5’,’.’,’4’
c. Call the function: Display_1D_Vector. This function will take in a vector of
characters as a parameter.
The function will output every character that exists in the vector.
Note: The main function’s loop will end when the user does not input a ‘Y’
or ‘y’ to indicate that they want to continue. You can assume that the user
will always input valid floating point numbers to convert.
2. The Float_To_Hex function should work for any valid non-negative floating-point
number. Each element of the vector that is returned will contain either a ‘.’ or
exactly 1 digit in the hex number. If there are no significant digits to the right of
the decimal place, the rightmost digit will contain a ‘0’.
