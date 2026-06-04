## Aim 
     To write a python Program using Destructor in class
## 🧠 Algorithm

1. Define a class named `Demo`.
2. Inside the class, define the `__init__` method:
   - Initialize an instance variable `status` with the value `"Alive"`.
   - Print the value of `status`.
3. Define the `__del__` method:
   - Print a message indicating the object is being destroyed.
4. Outside the class:
   - Create an instance of the `Demo` class.
   - Delete the object using the `del` keyword.
## Program
```
class demo:
    def __init__(self):
        self.status="Alive"
    def __del__(self):
        print("The object no longer exists")
a=demo()
print(a.status)
```

## 🧪 Output
<img width="964" height="219" alt="5b" src="https://github.com/user-attachments/assets/3f2f62f9-7862-4d2e-8d85-98cc7d10651e" />


## Result
Thus the  python Program using Destructor in class is done and output is verified
