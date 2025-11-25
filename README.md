Java Learning Exercises

This repository contains a collection of Java exercises demonstrating fundamental programming concepts, console applications, and GUI development using Swing. Each exercise focuses on a specific problem or programming concept, providing hands-on practice for beginners and intermediate learners.


Table of Contents

1. Fibonacci Series Calculator

2. Palindrome Checker

3. Factorial Calculator

4. Text Analyzer Pro (GUI)

5. Prime Number Checker (Recursive)

   

1. Fibonacci Series Calculator

Class: Exercise3

Generates the Fibonacci series up to a user-specified number of terms.

Features:

Accepts a non-negative integer from the user.

Generates the Fibonacci sequence iteratively.

Handles invalid input gracefully.

Example:
Enter number to count: 7
0, 1, 1, 2, 3, 5, 8,


2. Palindrome Checker

Class: Exercise6

Checks if a given string (word or name) is a palindrome.

Features:

Ignores case while checking.

Prints a clear message indicating the result.

Uses StringBuilder to reverse the string.

Example:
Enter Your Name: Anna
It is palindrome

Enter Your Name: John
It is not palindrome

3. Factorial Calculator

Class: Factorial

Calculates the factorial of a non-negative integer using iterative and recursive methods.

Features:

Input validation for non-negative integers.

Supports both iterative and recursive calculations.

Simple console-based interface.

Example:
Enter a non-negative number: 5
Choose a method:
1 → Iterative Factorial
2 → Recursive Factorial
Enter choice: 1
Factorial = 120

4. Text Analyzer Pro (GUI)

Class: TextAnalyzerPro

A professional GUI application to analyze text input and visualize character distribution.

Features:

Counts vowels, consonants, spaces, and punctuation.

Calculates percentage of each character type.

Displays results in a pie chart.

Dark-themed Swing GUI with responsive layout.

Example:

Enter text: "Hello, World!"

Output:

Vowels: 3
Consonants: 7
Spaces: 1
Punctuation: 2
Percentages: 18.8% vowels, 43.8% consonants, 12.5% punctuation, 6.3% spaces

5. Prime Number Checker (Recursive)

Class: PrimeRecursion

Checks whether a number is prime using recursion.

Features:

Efficiently checks divisors up to the square root of the number.

Handles edge cases (numbers ≤ 1).

Simple console output: true or false.

Example:
System.out.println(isPrime(29)); // Output: true
System.out.println(isPrime(10)); // Output: false
