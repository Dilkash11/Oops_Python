# Oops_Python
This repository consists of all the concepts related to object-oriented programming with Python.
#Class Method as alternative constructor
class Employees:
    def __init__(self, name, age, asalary):
        self.name = aname
        self.age = age
        self.salary = asalary

@classmethod 
    def from_slash(cls,string):
          return cls(*string.split("/"))

Alex=Date.from_dash("Alex/25/70000")
print(Alex.asalary)
#Output: 70000
