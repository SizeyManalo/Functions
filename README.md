# Functions
Functions in Python This code provides examples of functions in Python, which are reusable blocks of code that execute when called. Functions help encapsulate and organize code for better readability and maintainability. 

Functions
[ ]
#Function - Its a block of code which executes when we call it.
def example():
  print("Hi Everyone")
[ ]
example()
account_circle
Hi Everyone
[ ]
def dept(fname):
  print(fname + " helps to generate revenue")

dept("HR")
account_circle
HR helps to generate revenue
[ ]
def example_1(string):
  return len(string)
print("length of string is",example_1("Python Programming"))
account_circle
length of string is 18
[ ]
text = "This is function topic in python"
def anytext(any):
  '''
  input:
    anytext-str
  output:
    anytext-str
  '''
  output = text +any.upper()
  return output
[ ]
anytext('Hello Everyone')
account_circle

[ ]
def multiply(*numbers):
  total = 1
  for number in numbers:
    total *= number
  return total
[ ]
multiply(2,3,4,1,3)
account_circle
72
[ ]
def emp_1(** emp):
  print(emp)
[ ]
emp_1(id=1,name="Steve",age=26)
account_circle
{'id': 1, 'name': 'Steve', 'age': 26}
[ ]
#task - define a function for employees with string "emp works with", id, name and dept
def Emp(** E):
  print("Employee works with ",E)
[ ]
Emp(id=30,name="Mark",dept="Engineering")
account_circle
Employee works with  {'id': 30, 'name': 'Mark', 'dept': 'Engineering'}
[ ]
def employee_details(emp_id, name, dept):
    return print(name,"(",emp_id,")","works in",dept,"department.")
employee_details(30,"Mark","Sales")

account_circle
Mark ( 30 ) works in Sales department.
[ ]
Colab
