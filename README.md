 # Student Class Program

This is a simple Python program to store and display the details of a student.

## How it works

First, a `Student` class is created. It has three variables:

- `name` for the student's name
- `roll` for the roll number
- `marks` for the marks

Then an object `s1` is created from the `Student` class.

The details of Rahul are stored in the object and printed on the screen.

## Code

```python
class Student:
    def __init__(self):
        self.name = ""
        self.roll = 0
        self.marks = 0.0

s1 = Student()

s1.name = "Rahul"
s1.roll = 101
s1.marks = 87.5

print("Name:", s1.name)
print("Roll:", s1.roll)
print("Marks:", s1.marks)
Requirements

Python 3 is required to run this program. No extra libraries are needed.

How to Run

Save the program as student.py and run it using:

python student.py
Output
Name: Rahul
Roll: 101
Marks: 87.5
Class and Object

Student is the class used to store student information.

s1 is an object of the Student class.

The program assigns Rahul's name, roll number, and marks to the object and
then displays them.
