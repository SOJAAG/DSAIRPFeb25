# Walkthroughs
1. [Google Colab](https://colab.research.google.com/)

# Installations

1. [Python download link](https://www.python.org/downloads/)
2. [Visual Studio download link](https://code.visualstudio.com/download)
3. [Git bash installation link](https://git-scm.com/downloads) (Mac and Linux users can skip this step)
4. Visual Studio Code Extensions:
    - Jupyter (Microsoft)
    - Andromeda (Eliver Lara)
    - Black Formatter (Microsoft)
    - Flake8 (Microsoft)

## Checklist
1. Git bash terminal access in VS Code
2. Venv creation. 
```bash 
pip install jupyter
```
3. Jupyter notebook
```bash
jupyter notebook
```
4. Auto code correction

# Python Data Types
## Numeric Type
### Integer
integer represents a whole number
### Float
floating-point format represents a decimal number
### Complex
complex numbers, eg: 1+2i
## Text Type
### String
string is a sequence of characters enclosed by matching single (') or double (") quotes.
eg: "hello"

## Sequence Type

### List
A list object can be used to bundle elements together in Python. A list is defined by using square brackets [ ]. list is mutable.
 with comma separated values within the square brackets. eg: oplist=[1,2,3,].
 
### Tuple
 A tuple is a sequence of comma separated values that can contain elements of different types. Tuple is immutable. eg: my_tuple= (1,2,3).
 
### Range
 The range() function is a common approach for implementing counting in a for loop. 
 A range() function generates a sequence of integers between the two numbers given a step size.
 eg:  range(end) = range(3)
 range(start, end)= range(3,7)
 range(start, end, step)= range(3,10,2)

## Mapping Type
### Dictionary
A Python dictionary is a data type for storing the data in a key-value pair format.
eg: A = {"a": 97, "b": 98, "A": 65, "B": 66}.

to get keys : A.keys()
to get values: A.values() 
## Set Type
duplicate elements are not allowed. There is no order or indexing for set.
eg: my_set= {1,2,3}

## Boolean
gives True, False ouput.

## None Type
when there is no value to return, none datatype is used.

# Operators in Python

## Arithmetic Operators

### Addition : to add numbers, eg: 2+3

### Subtraction : to substract numbers, eg: 3-2

### Multiplication : to multiply numbers, 2*3

### Division : to divide numbers, will give result in float datatype. eg: 3\2

### Modulous : gives reminder value after division. eg: 4%2

### Exponent : gives exponential value, eg: 2**3

### Floor Division: gives quotient value after division, eg: 4//2

## Assignment Operator
assignment operators are " = , += , -= , *= "

## Comparison Operator
- > : greater than than
- < : less than
- >= : greater than or equal to
- <= : less than or equal to
- == : equal to
- != : not equal to

## Logical Operators

### AND

### OR

### NOT


## Membership Operator
### IN : to check whether a value is in the list. eg: 1 in [1,2,3] gives an output = True

### NOT IN : result will be a boolean value. eg: 1 no in [1,2,3] gives an output = False

## Identity Operator

### is : to check same memory location
### is not :to check same memory location

