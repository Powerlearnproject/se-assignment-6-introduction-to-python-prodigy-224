[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15311556&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
   Python is a high level programming language that supports multiple programming paradigms

   key features
   It is easy to read and write
   it is an interpreted language
   it offers extensive standard library

   use cases
   in web development
   data analysis
   machine learning and artificial intelligence
   Game development

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   Download the installer from the python website https://www.python.org/downloads/
   Run the installer and follow the set up instructions
   Check the box Add python to path during installation
   Verify installation by opening the command prompt and typing python --version

   setting up environment
   in the command prompt or even gitbash install the virtual environment by running pip install virtualenv
   create a virtual environment by running virtualenv myenv
   Activate the environment by using the following commands myenv\Scripts\activate



3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   print("Hello, World!")
   print is a built-in function in Python used to output text to the console.
   "Hello, World!" is a string literal enclosed in double quotes.


4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

  Integer (int): Whole numbers,
  Float (float): Numbers with a decimal point,
  String (str): Sequence of characters,
  Boolean (bool): True or False,

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
   if else
   x = 10
   if x > 5:
     print("x is greater than 5")
   else:
     print("x is not greater than 5")

   loops
    for i in range(5):
    print(i)



6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   Functions are reusable blocks of code that perform a specific task. They help in organizing code, making it more readable and maintainable.

   def add(a, b):
    return a + b

  # Calling the function
  result = add(3, 5)
print(result)  # Output: 8


7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

   Lists
   Ordered, mutable collections of items.
   numbers = [1, 2, 3, 4, 5]
   print(numbers[0])  # Output: 1

   Dictionaries
   Unordered collections of key-value pairs.
   student = {
    "name": "Alice",
    "age": 25,
    "is_student": True
     }
    print(student["name"])  # Output: Alice

    # List
   numbers = [1, 2, 3, 4, 5]
   numbers.append(6)
   print(numbers)  # Output: [1, 2, 3, 4, 5, 6]

    # Dictionary
   student = {"name": "Alice", "age": 25, "is_student": True}
    student["age"] = 26
    print(student)  # Output: {'name': 'Alice', 'age': 26, 'is_student': True}

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
   Exception handling allows a program to deal with unexpected errors gracefully. It uses try, except, and finally blocks.

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
   A module is a file containing Python code, and a package is a collection of modules.

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

   raeding:
    with open("example.txt", "r") as file:
    content = file.read()
    print(content)

    writing:
    lines = ["First line\n", "Second line\n", "Third line\n"]
    with open("output.txt", "w") as file:
    file.writelines(lines)



# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


