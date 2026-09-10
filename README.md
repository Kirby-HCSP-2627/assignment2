# Assignment #2

### INSTALL
For this assignment, you won't need to run any commands. 

### Intro
This assignment is for you to practice using if/else statements, for loops, and while loops
### Relevant Info 
When using cascading if/else statements, Python will continue checking the if statements until it sees an elif or else. Also take care with the order of your statements. 
```python
def get_letter_grade(score):
    if score >= 90:
        return "A"
    elif score >= 80:
        return "B"
    elif score >= 70:
        return "C"
    elif score >= 60:
        return "D"
    else:
        return "F"
```
The example above will correctly return the letter grade. 
```python
def get_letter_grade_incorrect(score):
    if score >= 60:        #Anything 60 or above stops here!
        return "D"
    elif score >= 70:
        return "C"
    elif score >= 80:
        return "B"
    elif score >= 90:
        return "A"
    else:
        return "F"
```
This example above will always return D if the score is 60 or above. It will not check any other score because of the first if statement. 

### The Program
#### Problem 1
Write a function fizz_buzz(n) that takes an int, n. The function will count up to number n starting from 1. There are 4 rules:
1. If the number is a multiple of 3, print “fizz”.
2. If the number is a multiple 5, print “buzz”.
3. If the number is a multiple of 3 and 5, print “fizzbuzz”.
4. Otherwise, print the number itself.

#### Problem 2
The Collatz conjecture states that if you take any positive integer, you will always eventually reach 1 by following two simple rules:
1. If the number is even, divide it by 2.
2. If the number is odd, multiply it by 3 and add 1.
<br/>
Write a function collatz_conjecture(num) that takes an integer and runs a while loop until the integer reaches 1. <br/>
At each iteration, print the number. <br/>At the end of the while loop, print the amount of steps it took to reach 1. 

### Example Output
No autograder test this time. I will be looking at your code! I have an example for each function in the python file! 

### Submitting 
To submit your project:
1. Open a terminal window in vscode in your project folder
2. run git add file_name.py , replacing it for whatever file you wrote code to
3. run git commit -m "Type your message in between the quotation marks. Your message should only be a couple words long and about what you changed"
4. run git push 
5. Confirm and check your auto-grade (if it's enabled) on your GitHub account, might take ~1 or 2 minutes to update on GitHub website
