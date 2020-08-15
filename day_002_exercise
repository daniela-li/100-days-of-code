# Exercises from Chapter 3: Conditionals https://books.trinket.io/pfe/03-conditional.html

# Exercise 1: Rewrite your pay computation to give the employee 1.5 times the hourly rate for hours worked above 40 hours.
# Enter Hours: 45
# Enter Rate: 10
# Pay: 475.0

pay = 0.0

input_hours = input("Enter Hours:")
input_rate = input("Enter Rate:")
hours = float(input_hours)
rate = float(input_rate)

if hours < 40:
    pay = rate * hours
    print("Pay: ",pay)
else:
    overtime = hours - 40.0
    pay = 1.5 * overtime * rate + rate * 40.0
    print("Pay: ",pay)

#Exercise 2: Rewrite your pay program using try and except so that your program handles non-numeric input gracefully by printing a message and exiting the program. The following shows two executions of the program:

# Enter Hours: 20
# Enter Rate: nine
# Error, please enter numeric input

# Enter Hours: forty
# Error, please enter numeric input

pay = 0.0
hours = 0.0
rate = 0.0

input_hours = input("Enter Hours:")
try:
    hours = float(input_hours)
except: 
    print("Error, please enter numeric input")
    quit()    


input_rate = input("Enter Rate:")
try:
    rate = float(input_rate)
except: 
    print("Error, please enter numeric input")
    quit()

if hours < 40:
    pay = rate * hours
    print("Pay: ",pay)
else:
    overtime = hours - 40.0
    pay = 1.5 * overtime * rate + rate * 40.0
    print("Pay: ",pay)

# Exercise 3: Write a program to prompt for a score between 0.0 and 1.0. If the score is out of range, print an error message. If the score is between 0.0 and 1.0, print a grade using the following table:
#
# Score   Grade
# >= 0.9     A
# >= 0.8     B
# >= 0.7     C
# >= 0.6     D
# < 0.6    F
# ~~~
# Enter score: 0.95 A ~~
#
# Enter score: perfect
# Bad score
# Enter score: 10.0
# Bad score
# Enter score: 0.75
# C
# Enter score: 0.5
# F
# Run the program repeatedly as shown above to test the various different values for input.

input_score = input("Enter score:")
try:
    score = float(input_score)
   
    if score > 0:
        if score > 1:
            print("Bad score")
        elif score >= 0.9:
            print("Score: A")
        elif score >= 0.8 :
            print("Score: B")
        elif score >= 0.7 :
            print("Score: C")
        elif score >= 0.6 :
            print("Score: D")
        elif score < 0.6 :
            print("Score: F")
        else:
            print("Bad Score")
except:
    print("Bad score")