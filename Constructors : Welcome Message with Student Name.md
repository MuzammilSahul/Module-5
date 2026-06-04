# # Constructors in Python: Welcome Message with Student Name

## 🎯 Aim
To write a Python program that creates a **Student** class with a **default constructor** and a method to display a welcome message along with the student’s name provided by the user.

## 🧠 Algorithm
1. **Get user input**: Accept the student's name from the user.
2. **Define the class**: Create a class `Student` with a default constructor (`__init__`).
3. **Default Constructor**: In the constructor, assign the user input (student name) to an instance variable `self.a`.
4. **Display Message**: Define a method `show` that prints "This is non-parameterized constructor" and a welcome message with the student’s name.
5. **Execute the Program**: Instantiate the `Student` class and call the `show` method.

## 🧾 Program
```
class student:
    def __init__(self):
        print("This is non parametrized constructor")
    def name(self,a):
        print("Hello",a)
a=input()
obj=student()
obj.name(a)
```

## Output
<img width="1045" height="274" alt="5a" src="https://github.com/user-attachments/assets/741be47a-37fd-4d02-a1cf-c03aa92406a7" />

## Result
Thus the Python program that creates a **Student** class with a **default constructor** and a method to display a welcome message along with the student’s name provided by the user is done and output is verified.
