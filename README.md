# COMP110 Worksheet 4

Please edit this README.md file with your answers to the worksheet questions.

## Question 1

### a
A | B | C | A AND B AND NOT C
-------------|-------------|-------------|-------------
False | False | False | False
False | False | True | False
False | True | False | False
False | True | True | False
True | False | False | False
True | False | True | False
True | True | False | True
True | True | True | False

### b
A| B | C | A AND NOT (B AND NOT C)|
-------------|-------------|-------------|-------------
False | False | False | False
False | False | True | False
False | True | False | False
False | True | True | False
True | False | False | True
True | False | True | True
True | True | False | False
True | True | True | True

### c
A | B | C | (A OR NOT B) AND (A OR C)
-------------|-------------|-------------|-------------
False | False | False | False
False | False | True | True
False | True | False | False
False | True | True | False
True | False | False | True
True | False | True | True
True | True | False | True
True | True | True | True

### d
A | B | C| D |A AND NOT (B OR NOT C) AND (NOT A AND D)
-------------|-------------|-------------|-------------|-------------
False | False | False | False | False
False | False | False | True | False
False | False | True | False | False
False | False | True | True | False
False | True | False | False | False
False | True | False | True | False
False | True | True | False | False
False | True | True | True | False
True | False | False | False | False
True | False | False | True | False
True | False | True | False | False
True | False | True | True | False
True | True | False | False | False
True | True | False | True | False
True | True | True | False | False
True | True | True | True | False


## Question 2

![Question_2_Answers](https://i.imgur.com/oHA3PJ5.png)

## Question 3

### a
A | B | NOT (A OR B)
-------------|-------------|-------------
False | False | True
False | True | False
True | False | False
True | True | False
IS the same as
A | B | NOT A AND NOT B
-------------|-------------|-------------
False | False | True
False | True | False
True | False | False
True | True | False

### b
A | B | NOT (A AND B)
-------------|-------------|-------------
False | False | True
False | True | True
True | False | True
True | True | False
IS the same as
A | B | NOT A OR NOT B
-------------|-------------|-------------
False | False | True
False | True | True
True | False | True
True | True | False

### c
A | B | C | (A AND B) OR (A AND C)
-------------|-------------|-------------|-------------
False | False | False | False
False | False | True | False
False | True | False | False
False | True | True | False
True | False | False | False
True | False | True | True
True | True | False | True
True | True | True | True
IS the same as
A | B | C | A AND (B OR C)
-------------|-------------|-------------|-------------
False | False | False | False
False | False | True | False
False | True | False | False
False | True | True | False
True | False | False | False
True | False | True | True
True | True | False | True
True | True | True | True

### d
A | B | C | (A OR B) AND (A OR C)
-------------|-------------|-------------|-------------
False | False | False | False
False | False | True | False
False | True | False | False
False | True | True | True
True | False | False | True
True | False | True | True
True | True | False | True
True | True | True | True
IS the same as
A | B | C | A OR (B AND C)
-------------|-------------|-------------|-------------
False | False | False | False
False | False | True | False
False | True | False | False
False | True | True | True
True | False | False | True
True | False | True | True
True | True | False | True
True | True | True | True

## Question 4

### a
If either, (./a.txt OR ./b.txt) does not exist then, print the message, (A required file is missing)
### b
If X is of type int (Integer) or float (Real) and X is greater than 7 then, print (Hello.)
### c
If X and Y are equal to 0 then, run method do something with no arguments.
### d
If X is less than 10 or (X and Y are greater than 0) then, run method do something with no arguments.
