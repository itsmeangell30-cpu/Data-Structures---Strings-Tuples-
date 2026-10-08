# Data-Structures---Strings-Tuples-
This repository contains Python programs and practice exercises based on Strings and Tuples. It covers basic operations, string methods, slicing, indexing, concatenation, replacing characters or words, counting occurrences, and accessing elements from tuples.

Data Structures – Strings & Tuples

Assignment Overview
This assignment focuses on understanding and implementing basic Python String and Tuple operations. The programs cover string concatenation, slicing, indexing, built-in string methods, tuple creation, concatenation, repetition, indexing, and slicing.

Tools Used
Python
Google Colab / Jupyter Notebook
GitHub

1. String Concatenation
Objective
Take the user's name as input, concatenate it with the string "Hello", and then add a welcome message.

Program
string1 = "Hello"
string2 = input("Enter your Name: ")
string3 = "Welcome to Python programming"

result = string1 + " " + string2 + ", " + string3

print(result)

Sample Output
Enter your Name: Zara
Hello Zara, Welcome to Python programming

2. String Slicing and Indexing
Using the concatenated string:

string = "Hello Zara, Welcome to Python programming"
a. Print the First Character
Program
print(string[0])

Output
H

b. Print the Last Character
Program
print(string[-1])

Output
g

c. Print the First 5 Characters
Program
print(string[:5])

Output
Hello

d. Print the Last 11 Characters
Program
print(string[-11:])

Output
programming

e. Print the String in Reverse
Program
print(string[::-1])

Output
gnimmargorp nohtyP ot emocleW ,araZ olleH

f. Print the Word "Python" Using Slicing
Program
print(string[21:27])

Output
Python

3. String Methods
For the following tasks, use:

strM = "Python beginner tutorial"

a. Convert the Sentence to Uppercase
Program
strM = "Python beginner tutorial"

print(strM.upper())

Output
PYTHON BEGINNER TUTORIAL

b. Convert the Sentence to Lowercase
Program
strM = "Python beginner tutorial"

print(strM.lower())

Output
python beginner tutorial

c. Capitalize the Sentence
The capitalize() method makes the first character uppercase and the remaining characters lowercase.

Program
strM = "Python beginner tutorial"

print(strM.capitalize())

Output
Python beginner tutorial

d. Count the Occurrences of Character 't'
The count() method is used to count how many times a character appears in a string.

Program
strM = "Python beginner tutorial"

print(strM.count('t'))

Output
3

e. Replace "Python" with "Data Analytics"
The replace() method replaces one string with another.

Program
strM = "Python beginner tutorial"

print(strM.replace("Python", "Data Analytics"))

Output
Data Analytics beginner tutorial

4. Tuples – Creation, Concatenation, Repetition and Access
Create two tuples:

tuple1 = (10, 20, 30)
tuple2 = (40, 50, 60)
a. Concatenate the Two Tuples
Program
tuple1 = (10, 20, 30)
tuple2 = (40, 50, 60)

t_combine = tuple1 + tuple2

print(t_combine)

Output
(10, 20, 30, 40, 50, 60)

b. Repeat the Elements of t_combine 3 Times
Program
tuple1 = (10, 20, 30)
tuple2 = (40, 50, 60)

t_combine = tuple1 + tuple2

print(t_combine * 3)

Output
(10, 20, 30, 40, 50, 60, 10, 20, 30, 40, 50, 60, 10, 20, 30, 40, 50, 60)

c. Access the 3rd Element from t_combine
Python indexing starts from 0, so the third element has index 2.

Program
print(t_combine[2])

Output
30

d. Access the First Three Elements
Program
print(t_combine[:3])

Output
(10, 20, 30)

e. Access the Last Three Elements
Program
print(t_combine[-3:])

Output
(40, 50, 60)

Concepts Learned
Through this assignment, the following Python concepts were practiced:

Creating and manipulating strings
String concatenation using +
String indexing
String slicing
Reverse slicing
String methods
Using upper()
Using lower()
Using capitalize()
Using count()
Using replace()
Creating tuples
Concatenating tuples
Repeating tuples using *
Accessing tuple elements
Tuple slicing
Assignment Deliverables
The complete assignment was implemented using Google Colab/Jupyter Notebook.

Conclusion
This assignment provides practical experience with fundamental Python data structures, especially Strings and Tuples, and demonstrates how indexing, slicing, built-in methods, concatenation, and repetition are used in Python programming.
