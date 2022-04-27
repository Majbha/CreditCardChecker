# CreditCardChecker


# There are 15 arrays that each contain the digits of separate credit card numbers. They all have prefixes to reflect their status, i.e. variables that start with 
valid contain a valid number, whereas invalid do not, and mystery variables can be either. There is also a batch array that stores all of the provided credit cards 
in a single array.

#To find out if a credit card number is valid or not, use the Luhn algorithm. Generally speaking, an algorithm is a series of steps that solve a problem —
the Luhn algorithm is a series of mathematical calculations used to validate certain identification numbers, e.g. credit card numbers. 
The calculations in the Luhn algorithm can be broken down as the following steps:

1) Starting from the farthest digit to the right, AKA the check digit, iterate to the left.
2) As you iterate to the left, every other digit is doubled (the check digit is not doubled). If the number is greater than 9 after doubling, subtract 9 from its value.
3) Sum up all the digits in the credit card number.
4) If the sum modulo 10 is 0 (if the sum divided by 10 has a remainder of 0) then the number is valid, otherwise, it’s invalid.
