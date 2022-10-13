### Python OOP
### 4 pillars of OOP
### Methods/Function
### Modules
### Packages
### Libraries
```python
# lucky draw
# key word called import
# import random
# from random import *
# import math

# print(random)

#print(random.random())
# print(random())

# each time it's run it generates a random number - 0-1

# calculate DOB or year of birth

# from random import *
import math


number = 23.66
# any numbers - round this figure up
# number 1.50 above to round up 2
# numbers 1.49 or less to round down 1
print(math.ceil(number)) # ceil will help you round up
print(math.floor(number)) # floor will help you round down

```
# Lucky draw
# Key word called import
# Import random
# From random import *
# Import math
# Import datetime
# Print(random)

# print(random.random())

# print(random())

# each time it's run it generates a random number - 0-1

# calculate DOB or year of birth


# from random import *
# import math
# import datatime, sys
# import os
# import sys
#
```python
 print(os.cpu_count()) # this will result in the number of cpu
 print(datetime.date.today()) # this will result todays date
 print(sys.path)

```
# Examplar Rounding Up/Down:
```python
# number = 23.66
# # any numbers - round this figure up
# # number 1.50 above to round up 2
# # numbers 1.49 or less to round down 1
# print(math.ceil(number)) # ceil will help you round up
# print(math.floor(number)) # floor will help you round down
```
# Explanation:

```commandline
# Don't Repeat Yourself (DRY)
- reusable - saves time - saves effort - saves money
- let's build some functions
- its part of the exam
# # syntax def name(): - def name() - daf name(): - def name:
# def greeting():
# greet the user
```
```python
print("Hello Dear")
# pass
# keyword called pass
#  #unless the function is called it does nothing
# greeting()
```


# Addition / Greeting User
```python
 def greet_user(name): # create a function that takes an argument - the name
     print("Hello Dear " + name) # adding 2 string with user input()
#    #pass

  greet_user("Ayoub")
  def add(value1, value2): # take user input at int the add them together display the outcome
# print("this function is to provide addition functionality)
# # # return statement
      return value1 + value2
# if you are using a return statement and calling the function it needs to be in a print st.
  add(2, 2,)
  print(add(2, 2))
```



### Multiply Task
```python
def multiply(value1, value2):
    return value1 * value2
# multiply(20, 5,)
print(multiply(20,5))
```
### Divide Task
```python
def divide(value1, value2):
    return value1 / value2
# divide(20, 5,)
print(divide(20,5))
```
### Modulo Task
```python
def Modulo(value1, value2):
    return value1 % value2
# Modulo(20, 5,)
print(Modulo(20,5))
```
### Own Example with Subtract "-"
```python
def subtract():
    print(10 - 3)
subtract()
```
