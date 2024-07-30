[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15465116&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
o	Python is a popular, high-level, dynamically typed programming language known for its readability and versatility.
o	Key features:
	Readable syntax: Python emphasizes clean, easy-to-understand code.
	Rich standard library: Python provides a wide range of built-in modules and functions.
	Cross-platform: Python runs on Windows, macOS, and Linux.
	Dynamic typing: Variables are not explicitly declared with types.
	Interpreted: Python code is executed line by line.
o	Use cases:
	Web development: Django and Flask frameworks.
	Data science: Pandas, NumPy, and SciPy.
	Automation: Scripting tasks.
	Machine learning: Libraries like TensorFlow and PyTorch

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
o	Download Python from the official page 
o	Verify installation by running python --version.
o	Set up a virtual environment using venv or virtualenv

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
Python
# Hello, World! program
print("Hello, World!")
o	Explanation:
	print() function displays text.
	"Hello, World!" is a string enclosed in double quotes

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
o	Basic data types:
	Integers: 42
	Floats: 3.14
	Strings: "Hello"
	Booleans: True or False
o	Variable assignment:
Python
name = "Alice"
age = 30

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
o	Conditional (if-else):
Python
if age >= 18:
    print("Adult")
else:
    print("Minor")
o	Loop (for loop):
Python
for i in range(5):
    print(i)

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
Python
def add(a, b):
    return a + b

result = add(10, 20)
print(result)  # Output: 30

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
o	Lists (ordered, mutable):
Python
numbers = [1, 2, 3, 4]
numbers.append(5)
o	Dictionaries (key-value pairs):
Python
person = {"name": "Bob", "age": 25}
print(person["name"])  # Output: "Bob"

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use 
Python
try:
    result = 10 / 0
except ZeroDivisionError:
    print("Error: Division by zero")
finally:
    print("Cleanup")

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
o	Modules: Reusable code files (e.g., math, random).
Python
import math
print(math.sqrt(16))  # Output: 4.0
.
o	Packages: Organized collection of modules

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
o	Reading from a file:
Python
with open("myfile.txt", "r") as file:
    content = file.read()
    print(content)
o	Writing to a file:
Python
data = ["apple", "banana", "cherry"]
with open("fruits.txt", "w") as file:
    for item in data:
        file.write(item + "\n")


# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


