# Robot Exam Coding Assignment

## Introduction @unplugged
In this activity, students are introduced to:

Expressing numeric operations with math operators (+, -, *, /)
Storing the result of an equation in a variable
Evaluating equations using variables
Modifying and creating variable equations
Displaying text with ``||adventure||`` code
Differentiating between the number and string data types

## Example 1: Math equation in a variable
In the ``||variables||`` category grab the ``||variables:item=0||`` code

```python
  item = 0
```

## Example 1: Math equation in a variable part 2
Change item to answer and 0 to 3+5

```python
  answer = 3 + 5
```

## Example 1: Math equation in a variable part 3
Next grab a ``||adventure:add text to text log||`` code and put it under the answer variable.

```python
  answer = 3 + 5
  adventure.add_to_textlog("")
```

## Example 1: Math equation in a variable part 4
Write "3 + 5 = " + str(answer) inside the parentheses of the ``||adventure:add text to text log||`` code. Run the code and see what prints.

```python
  answer = 3 + 5
  adventure.add_to_textlog("3 + 5 = " + str(answer))
```

## Example 1: Math equation in a variable part 5
Experiment using different numbers in our equation (e.g. 9 + 2)
Test at least 3 different equations
Challenge: make longer addition equations with Math blocks so that the code calculates the sum of 5 or more numbers. If the equation gets too long, then display using show long text

```python
  #Math operations
  #Addition
  1+1
  #Subtraction
  1-1
  #Multiplication
  1*1
  #Division
  1/1
```

## Example 2: Math equation in a variable part 1
Change answer to 0
Add two new ``||variables:item=0||`` under the answer named ``||variables:first_number||`` and ``||variables:second_number||``

```python
  answer = 0
  first_number = 0
  second_number = 0
  adventure.add_to_textlog("3 + 5 = " + str(answer))
```

## Example 2: Math equation in a variable part 2
Redeclare ``||variables:first_number||`` and ``||variables:second_number||`` with new values.  

```python
  answer = 0
  first_number = 0
  second_number = 0
  first_number = 15
  second_number = 5
  adventure.add_to_textlog("3 + 5 = " + str(answer))
```

## Example 2: Math equation in a variable part 3
Redeclare answer to be first_number - second_number. Then change the ``||adventure:add text to text log||`` to 15-5

```python
  answer = 0
  first_number = 0
  second_number = 0
  first_number = 15
  second_number = 5
  answer = first_number - second_number
  adventure.add_to_textlog("15-5 = " + str(answer))
```

## Example 2: Math equation in a variable part 4
Redeclare ``||variables:first_number||`` and ``||variables:second_number||`` with new values below your ``||adventure:add text to text log||`` code.
Then redeclare answer and set it equal to  ``||variables:first_number||`` plus ``||variables:second_number||``.  Then update a new ``||adventure:add text to text log||`` below to update the statement.

```python
  answer = 0
  first_number = 0
  second_number = 0
  first_number = 15
  second_number = 5
  answer = first_number - second_number
  adventure.add_to_textlog("15-5 = " + str(answer))
  #Redeclare first_number and second_number here:
```

