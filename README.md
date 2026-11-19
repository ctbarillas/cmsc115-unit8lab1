# Lab Reflection: Unit 8 Lab 1 - Git Version Control + Debugging (BuggyProgram)

## Student Name
Cody T. Barillas

## GitHub Repository URL
https://github.com/ctbarillas/cmsc115-unit8lab1.git

---

# Commit 1: Initial Commit

## What did you include in this commit?
- I chose all the original files.

## What was the purpose of this commit?
- To establish a baseline for my code.

---

# Commit 2: Task 1 (getGrade)

## Which tests in Task1Test were failing before your fix?
- The edgeCases and testGrades tests were failing. 

## What was the issue in the code?
- The issue was the ranges for the user score. The values for exceeds and
- meets were swapped, and the use of the > symbol instead of >= was causing
- an overlap in how the scoring was processed. 

## What change did you make to fix it?
- I changed it so that a score >= 90 would output "Exceeds" >= 80 but < 90
- would output "Meets" and anything else would output "Does not meet"

## How did the tests help guide your fix?
- The tests showed me the expected outcome which I used to correct 
- my code. 

---

# Commit 3: Task 2 (sumEvenNumbers)

## Which tests in Task2Test were failing before your fix?
- testEmpty, testOddNumbers, testSumEvenNumbers all failed.

## What was the issue in the code?
- int sum = 1; should be initialized to int sum = 0; and the condition 
- of the for loop was incorrect.

## What change did you make to fix it?
- I changed int sum = 1; to int sum = 0; and changed the condition of the
- for loop to read i < values.length;

## How did the tests help guide your fix?
- They gave me an Out of Bounds error which led me to think of the
- condition causing the iteration of the array to fail and once I fixed 
- that, I ran the test again and saw that sum = 1 was causing the rest 
- of the erroneous outputs. 

---

# Commit 4: Task 3 (sumRange)

## Which tests in Task3Test were failing before your fix?
- testSumRangeReverseOrder fails

## What was the issue in the code?
- The original code did not account for if the user enters the values
- in reverse order, with the bigger number first. 

## What change did you make to fix it?
- I added in an if else statement with nested for loops to account 
- for this. Now the code can count up and count down. 

## How did the tests help guide your fix?
- The tests made it very straightforward once I saw the expected vs
- actual output. I did the math and knew how to fix it. 

---

# Overall Reflection

## Which task was the easiest to fix? Why?
-

## Which task was the most difficult? Why?
-

## How did Git help you track your progress through the debugging process?
-

## Why is it important to make small, frequent commits when debugging code?
-

## What did you learn about using JUnit tests to guide debugging?
-

---

# Commit 5: Final Reflection

## What did you complete or update before making this final commit?
-

## Why is it useful to document your work after completing a programming task?
-