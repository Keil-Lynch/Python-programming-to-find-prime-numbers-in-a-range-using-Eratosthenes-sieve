# Python-programming-to-find-prime-numbers-in-a-range-using-Eratosthenes-sieve
Using the Sieve of Eratosthenes, the program prints the prime numbers in a range.

Python programming to find prime numbers in a range using Eratosthenes' sieve

It uses the Sieve of Eratosthenes to print prime numbers in a range.

Problem Description

Using the Sieve of Eratosthenes, the program prints the prime numbers in a range.

Problem Solution

Get the user's value of n.
Place numbers 2 to n at the beginning of the sieve.
Create a while loop that checks to see if the sieve is empty
Determine the smallest prime number
Eliminate that number and its multiples
Remove the sieve once it is empty
Make your exit

Program Explanation

An upper limit of range must first be entered by the user, and stored in a variable n.
Initialized to a set that ranges from 2 to n (not including n+1).
To ensure that the sieve is not empty, the while loop is used.
In this case, prime is initialized with the least number in the sieve and printed.
All prime numbers with multiples of the sieve are then removed.
Steps 4 and 5 are repeated until the value of the sieve disappears.

Test Case Study (Run Program)

(Console Prompt)Enter upper limit of range: (User Input) 20

(Output)2	3	5	7	11	13	17	19
