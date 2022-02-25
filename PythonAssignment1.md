## Assignment 1
# 1. In the below elements which of them are values or an expression? eg:- values can be integer or string and expressions will be mathematical operators.
  
answers:- 
* => multiplication
'hello' => string
-87.8 => float
- => subtraction
/ => divishion
+ => addition
6 => integer(int)

```python
a = 10
b = 20
print(type("hello"))
print(a * b)
print(type(-87.8))
print(a - b)
print(a / b)
print(a + b)
```

    <class 'str'>
    200
    <class 'float'>
    -10
    0.5
    30
    
2. What is the difference between string and variable?
answers:
string => string is an array of sequenced characters, string will written in single, double, and triple quotes 
ex: 'hari', "krishna", """Python Lover"""

variable => Variable is which is refer to memory location, when we assign a particular value to the 
variable it store the values reference or memory location.
ex:
name = "Hari Krishna"
name is variable 
"Hari Krishna" is value

```python
name = "Hari krishna"
name
```




    'Hari krishna'


3. Describe three different data types.
answer: There are 3 data types Strings, List, Tuples
string = string is an array of sequenced characters, string will written in single, double, and triple quotes
List = It is store multiples of elements, It supports all data types
boolen = boolens are most powerfull in python, True and False, They behave like the integers 0 and 1.4. What is an expression made up of? What do all expressions do?
answer: Expressions are made up of operators and values(or operands), All expressions return a value after evaluating them5. This assignment statements, like spam = 10. What is the difference between an expression and a statement?
answer: Expression here is spam = 10, we have assigned a value 10 to variable spam, Assignment statement is ‘=’ that is used to assign the values, An expression is a sequence of operators and values that produce/return a value and statements are instructions or code that python interpreter can execute6. After running the following code, what does the variable bacon contain?

bacon = 22

bacon + 1

answer: 237. What should the values of the following two terms be?

'spam' + 'spamspam'

'spam' * 3

answer: ’spam’ + ‘spamspam’ returns ‘spamspamspam’

‘spam’ * 3 returns ‘spamspamspam’8. Why is eggs a valid variable name while 100 is invalid?

answer: Variable name have a particular syntax for assignment

eggs is valid because variable name start from either a character or _

but 100 is invalid because it starts from a number, the compiler cannot recognize it as a variable and gives an error9. What three functions can be used to get the integer, floating-point number, or string version of a value?

answer: int() function can be used to convert into integer, float() to get a floating point value and str() to get a string value10. Why does this expression cause an error? How can you fix it?

'I have eaten ' + 99 + ' burritos.'

answer: This expression causes an error because we are trying to add a integer to a string which cannot be evaluated unless we convert the integer to a string

This can be fixed by

‘I have eaten’ + ‘ 99’ + ‘ burritos’