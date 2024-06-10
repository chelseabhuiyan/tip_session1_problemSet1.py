# tip_session1_problemSet1.py
# Problem Set Version 1
## Problem 1: Hello World!
Given the following lines of code, work with your group members to place the lines in order and write and call your first Python function!

a. print("Hello world!")
b. def hello_world():
c. hello_world()

💡 Hint: Functions

## Problem 2: Today's Mood
The following function uses a variable, mood to print out "Today's mood: 😎". Copy this code to your Replit and update the mood variable to print out your mood for today.

def todays_mood():
    mood = "😎"
    print("Today's mood: " + mood)

todays_mood()

Example Output: Today's mood: 🥱

💡 Hint: Variables

## Problem 3: Lunch Menu
The following function accepts one parameter menu. Copy this code to your Replit and add a function call so that "Lunch today is: 🍕" is printed to the console.

def print_menu(menu):
    print("Lunch today is: " + menu)
Example Output: Lunch today is: 🍜

💡 Hint: Parameters
💡 Hint: Parameters, Arguments, and Variables Oh My!

## Problem 4: Sum of Two Integers
The following function returns the sum of two integers: a and b.

def sum(a, b):
    return a + b
Use the sum() function to calculate the sum of 13 and 27. Then, double the calculated sum and print the result to the console.

Example Input: 20 and 8
Example Output: 56


## Problem 5: Product of Two Integers
Write a function product() that returns the product of two integers, a and b.

Example Input: 22 and 7
Example Result: 154

💡 Hint: To Print or to Return?

## Problem 6: Classify Age
Write a function classify_age() that takes an integer age as a parameter and returns "child" if the age is less than 18, and returns "adult" otherwise.

Example Usage:

output = classify_age(18)
print(output)
output = classify_age(7)
print(output)
output = classify_age(50)
print(output)
Output:

adult
child
adult
💡 Hint: Conditionals

## Problem 7: What time is it?
Let's put what we learned in Problems 1-4 all together! Write a function named what_time_is_it() that takes an integer hour as a parameter.
If hour is 2, the function should return "taco time 🌮".
If hour is 12, the function should return "peanut butter jelly time 🥪”.
Otherwise, the function should return "nap time 😴".

Example Usage:

time = what_time_is_it(2)
print(time)
time = what_time_is_it(7)
print(time)
time = what_time_is_it(12)
print(time)
Output:

taco time 🌮
nap time 😴
peanut butter jelly time 🥪

## Problem 8: Blackjack
In the game Blackjack, players try to draw a hand of cards that totals as close to 21 as possible. Players "bust" if their cards total more than 21. Players say "Hit me!" if they want the dealer to give them another card.

Write a function called blackjack() that takes an integer score as a parameter.
If score equals 21, print "Blackjack!".
If score is greater than 21, print "Bust!".
If score is greater than or equal to 17 and less than 21, print "Nice hand!".
If score is less than 17, print "Hit me!".

Example Usage:

blackjack(24)
blackjack(19)
blackjack(21)
blackjack(10)
Output:

Bust!
Nice Hand!
Blackjack!
Hit me!

## Problem 9: First Item
Write a function get_first() that takes in a list as a parameter and returns the first item in the list. Return None if the list is empty.

def get_first(lst):
    pass
Example Input: [3,1,6,7,5]
Example Output: 3

Note: pass is a keyword that is used as a placeholder for future code

💡 Hint: List Indexing

## Problem 10: Last Item
Write a function get_last() that takes in a list as a parameter and returns the last item in the list. Return None if the list is empty.

def get_last(lst):
    pass
Example Input: [3,1,6,7,5]
Example Output: 5

💡 Hint: Getting the length of the list

## Problem 11: Counter
Write a function counter() that uses the range function to print numbers between 1 and a given stop value (inclusive).

def counter(stop):
    pass
Example Usage: counter(7). Example Output:

1
2
3
4
5
6
7
💡 Hint: For Loops
💡 Hint: range()

## Problem 12: Sum of 1 to 10
Write a function sum_ten() that returns the sum of numbers from 1 to 10.

def sum_ten():
    pass
Example Usage: output = sum_ten()
Example Result: output = 55

💡 Hint: Accumulator Variable

## Problem 13: Total Sum
Write a function sum_positive_range() that returns the sum of numbers from 1 to a given stop value (inclusive).

def sum_positive_range(stop):
    pass
Example Usage: sum = sum_positive_range(6)
Example Result: sum = 21


## Problem 14: Total Sum in Range
Write a function sum_range() that returns the sum of numbers from a given start value to a given stop value (inclusive).

def sum_range(start, stop):
    pass
Example Usage: sum = sum_range(3, 9)
Example Result: sum = 42


## Problem 15: Negative Numbers
Write a function print_negatives() that takes a list of integers lst and prints all negative numbers in the list.

def print_negatives(lst):
Example Usage: print_negatives([3,-2,2,1,-5])
Example Output:

-2
-5
Example Usage: print_negatives([1,2,3,4,5])
Example Output:

None
