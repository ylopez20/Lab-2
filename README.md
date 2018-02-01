# Lab-2

For this lab, I want you to generate code (based upon what is in the Chapter-3 notes) to solve 1 of these problems.

Please Fork this repository to your GitHub repository, and then clone this to your computer.  Once you have it cloned, create a folder with your name or GitHub id.  Inside this folder is where all the files you work on should be kept, and handed in from.  This can include notes, flowcharts, false starts, etc.  It should inlcude the code that you generate for one of these problems.

Note this does not need to be able to be executed/run as java code, but I do want the logic of the program to be there.  This also mans that if you have statements taht are too broad in your flow chart, or psuedo code, then you need to break those down into multiple smaller steps.

## Problem 1
### String permutations
You program will be given a word (all letters, no spaces or other symbols) that is less than 50 characters in length.  Your program needs to print out every rearrangement of the letters (you can do this as if every letter was different, so you do not need to check if you have duplicate letters in the word) and then print out how many there were in total.

## Problem 2
### The 3n + 1 problem
Your program will be given a positive number (less than 10,000).  Your program will take the number and follow the appropriate step below:

  * when n is even, divide n by 2
  * when n is odd, multiply n by 3, and then add 1
  
When n is equal to one you stop, otherwise you pick the appropriate step again.

Please print out the sequence of numbers that lead to 1, starting with n, and how many times (in sumation) the above two commands are run.

## Problem 3
### Guessing Game
Your program will pick a number (you will use getRandomNumber ) between 0 and 100, then the user will guess a number.  The computer will tell if the guess is correct, too low, or too high.  When the user guesses the correct number, the program should print out how many guesses it took.
