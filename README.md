# Java
project lesson2-V_Trigubovich 
/ package com.belhard.lesson2.linear
each task in a separate class with own main method
1. Find the value of the function: z = ( (a - 3) * b / 2) + c
2. Given a real number R of the form nnn.ddd (three digits in the fractional and integer parts). Swap the fractional and integer parts of the number and output the resulting value of the number.
3. Given a natural number T, which represents the duration of the elapsed time in seconds. Output the given duration value in hours, minutes, and seconds in the following form: HHh MMmin SSs.(For example: 14h 22min 07s)
4. Calculate the value of the expression using the formula (all variables take real values):
(b+√(b^2+4ac))/2a-a^3 c+b^(-2)
5. Calculate the value of the expression using the formula (all variables take real values):
(sin x+cos y) / (cosx-siny) *tg xy
/ package com.belhard.lesson2.branching
each task in a separate class with own main method
1. Find max{min(a, b), min(c, d)} - i.e. the maximum value of two expressions, in the first of which we find the significant of the two numbers, and in the next, the significant of the other two. Use only the conditional jump operator or ternary operator. It is forbidden to use Math.max() and Math.min()
2.	Calculate function value:
	y={ (x^2-3x+9, if x≤3; 1/(x^3+6), if x>3
3.	Two angles of a triangle are given (in degrees). Determine whether such a triangle exists, and if so, whether it is a right triangle. (A triangle cannot exist unless the sum of its angles is 180)
/ package com.belhard.lesson2.cycles
1. Write a program where the user enters any positive integer. And the program sums up all numbers from 1 to the number entered by the user.
2. Calculate the values of the function on the segment [a,b] with step h:
y= {(x+4, if x>2; -x*2,if x≤2
3. Find the sum of the squares of the first hundred numbers.
4. Display the correspondence between the serial numbers of symbols and their graphical representation - i.e. an ASCII table (remember that the first 32 characters of the table are non-printable).
For example:
64 -> @ 65 -> A 66 -> B
67 -> C 68 -> D 69 -> E
5. Write a program for finding the product of squares of the first two hundred numbers (you can look towards java.math.BigInteger / java.math.BigDecimal)

project lesson3-V_Trigubovich
/ package com.belhard.lesson3.arrays. onedimentional
1. An array of length N contains natural numbers. Find the sum of those elements that are multiples of a given K.
2. An array of real (including fractional) numbers is given, the dimension of which is N. Calculate how many negative, positive and zero elements it contains.
3. Given a sequence of integers a1, a2, ..., an. Form a new sequence by removing from the original those terms that are equal to min(a1 ,a2 ,..., an) – i.e. the smallest number in this sequence.
/ package com.belhard.lesson3.arrays.multidimentional
1. Given a two-dimensional array. Display it as a matrix.
For example:
for {{0, 1, 2, 3, 4}, {10, 11, 12, 13, 14}, {20, 21, 22, 23, 24}, {7, 7, 7, 7, 7}}
The output will be ->
   0 1 2 3 4
10 11 12 13 14
20 21 22 23 24
   7 7 7 7 7
2. Sort the rows of the matrix in ascending and descending order of element values (the user can choose how). Those. the elements within each individual row must be sorted. For sorting, you can use java.util.Arrays.sort()
/ package com.belhard.lesson3.arrays.sorting
1. Implement bubble sort for an array of integers (Bubble sort)
