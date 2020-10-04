# HackerRank Challenges in Python

### Challenge: Drawing Book
Solve the problem of what is the minimum number of pages you need to turn to get to page p.
- You can turn from the front or back of a book with n number of pages.
- You can only turn one page at a time.

For example: You will turn 0 pages to get to page 4 in a 5 page book.

### Challenge: Counting Valleys
How many valleys did the hiker go through?
- Starting and ending at 0, D is +1, U is -1.
- A valley is counted when the hiker goes down and comes back up to 0.

### Challenge: Electronics Shop
Spend as much of the money as possible in the budget getting both keyboard and USB drive.
- Budget = int
- Keyboards = array
- Drives = array
- Add up the arrays in every combination to get the max dollar amount without being over the budget and return the dollar amount
- If over return -1

### Challenge: Cats and a Mouse
Which of the two cats will get the mouse or will the mouse get away?
- if Cat A (x) is closer print 'Cat A'
- if Cat B (y) is closer print 'Cat B'
- if they are equal distance then they will fight and the mouse (z) will get away print 'Mouse C'

### Challenge: Forming a Magic Square
What is the minium cost to convert a 3x3 matrix into a magic square?
- all rows, columns, diagonals add up to 15
- only distict integers 1 through 9 can be used
- return only the cost

### Challenge: Picking Numbers
Complete the pickingNumbers function.
- Return an integer theat represents the lenght of the longest array that can be created
- The difference between any two of the chosen integers in the array is less than or equal to 1

### Challenge: Climbing the Leaderboard
Track the leaderboard ranking using dense ranking
- the player with the highest score is ranked number 1
- the players who have equal score receive the same ranking number
- the next players receive the immediately following ranking number

### Challenge: Jumping on the Clouds
Figure out the minimum number of jumps needed
- can only jump on a 0
- can only jump plus 1 or 2

### Challenge: List Comprehensions
Let's learn about list comprehensions! You are given three integers x, y and z representing the dimensions of a cuboid along with an integer n. Print a list of all possible coordinates given by (i, j, k) on a 3D grid where the sum of i + j + k is not equal to n. Please use list comprehensions rather than multiple loops, as a learning exercise.

### Challenge: Find the Runner-Up Score!
Given the participants' score sheet for your University Sports Day, you are required to find the runner-up score. You are given n scores. Store them in a list and find the score of the runner-up.

### Challenge: Nested Lists
Given the names and grades for each student in a class of N students, store them in a nested list and print the name(s) of any student(s) having the second lowest grade.
Note: If there are multiple students with the second lowest grade, order their names alphabetically and print each name on a new line.


## 30 Day Challenges
### Day 2 Operators
Worked on math problem to find the total cost of a meal
- given cost of meal
- given percent tip
- given percent tax
- tally up to the nearest integer

### Day 3 Intro to Conditional Statements
Given an integer, , perform the following conditional actions:
- If n is odd, print Weird
- If n is even and in the inclusive range of 2 to 5, print Not Weird
- If n is even and in the inclusive range of 6 to 20, print Weird
- If n is even and greater than 20, print Not Weird

### Day 4 Class vs. Instance
Write a Person class with an instance variable, age, and a constructor that takes an integer, initialAge, as a parameter. The constructor must assign initialAge to age after confirming the argument passed as initialAge is not negative; if a negative argument is passed as initialAge, the constructor should set age to 0 and print Age is not valid, setting age to 0.. In addition, you must write the following instance methods:
- yearPasses() should increase age by 1
- amIOld() should perform the following:
  - if age < 13 print You are young..
  - if age >= 13 and age < 18, pring You are a teenager..
  - otherwise print You are old..

### Day 5 Loops
Given an integer, n, print its first 10 multiples. Each multiple n x i (where 1 <= i <= 10) should be printed on a new line in the form: n x i = result.

### Day 6 Let's Review
Given a sting, S, of length N that is indexed from 0 to N -1, print its even-indexed and odd-indexed characters as 2 space-separated strings on a single line. Note: 0 is considered to be an even index.

### Day 7 Arrays
Given an array, A, of N integers, print A's elements in reverse order as a sigle line of space-separated numbers.

### Day 8 Dictionaries and Maps
Given n names and phone numbers, assemble a phone book that maps a friends' names to their respective phone numbers. You will then be given an unknown numner of names to query your phone book for. For each name queried, print the associated entry from your phone book on a new line in the form:
- name = phoneNumber
- if name is not found print Not found

### Day 9 Recursion 3
Write a factorial function that takes a positive integer, N as a parameter and prints the result of N! (N factorial)

### Day 10 Binary Numbers
Given a base-10 integer, n, converti it to binary (base-2). Then find and print the base-10 integer denoting the maximum number of consecutive 1's n n's binary representation.

