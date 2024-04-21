Input: A decimal number, e.g., 65, 65.0, 65.5, 0.0065, 1, 123456789, etc.
Output: The contents of the 4 bytes of memory in hex (first byte first) if the input number is stored as a float.
Sample run #1:
Enter a decimal value: 65.0 <enter>
0x42820000
Sample run #2:
Enter a decimal value: 0.0065 <enter>
0x3bd4fdf4
So based on the restriction stated above, you cannot use unions or pointers.
Your code will be tested on different values than those given as examples above.
