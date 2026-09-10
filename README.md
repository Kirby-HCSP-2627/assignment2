# Assignment #2

### INSTALL
For this assignment, you won't need to run any commands. 

### Intro
This assignment is for you to practice using if/else statements, for loops, and while loops
### Relevant Info 
When using cascading if/else statements, Python will continue checking the if statements until it sees an elif or else. Also take care with the order
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
You will not need to create a file this time around. Open the python file named assignment.py. In the file you will find the questions to answer. Careful to not change the name of this file, I will be running an auto grader!

### Example Output
Check auto-grader tests! 

### Submitting 
To submit your project:
1. Open a terminal window in vscode in your project folder
2. run git add file_name.py , replacing it for whatever file you wrote code to
3. run git commit -m "Type your message in between the quotation marks. Your message should only be a couple words long and about what you changed"
4. run git push 
5. Confirm and check your auto-grade (if it's enabled) on your GitHub account, might take ~1 or 2 minutes to update on GitHub website
