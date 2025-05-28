# Experiment No: 1a Python Basics- Printing Multiline String

## AIM  
To create a Python program to print the string in multiple lines using triple quotes.

## ALGORITHM  
1. Begin the program.  
2. Use triple quotes (`'''` or `"""`) to define a string that spans multiple lines.  
3. Use the `print()` function to display the multi-line string.  
4. Terminate the program.

## PROGRAM
```python

string_single_quotes = '''I am a string literal
... has more than one
... line
... placed inside triple single quotes'''

string_double_quotes = """I am a string literal
... has more than one
... line
... placed inside triple double quotes"""

print(string_single_quotes)
print(string_double_quotes)
```
## OUTPUT
![image](https://github.com/user-attachments/assets/5f00ee07-dc40-4c28-8d34-8d9529ae342f)

## RESULT
Thus, the Python program to print a string in multiple lines using triple quotes was implemented and executed successfully.

Experiment No: 1B – Data Types – Identifying Literal Types
AIM
To write a Python program to read the input from the user and print the type of the literal using eval().

ALGORITHM
Begin the program.
Read input from the user using input().
Use eval() to evaluate the input to its actual data type.
Use type() function to identify the type of the evaluated input.
Print the identified type.
Terminate the program.
PROGRAM
data = input()
data1 = eval(data)
print(type(data1))
OUTPUT
image

RESULT
Thus the Python program Identifying Literal Types have been implemented and executed successfully.


# Experiment No: 1c – Variables and Expressions, Operators – Celsius to Fahrenheit Conversion

## AIM  
To write a Python program to convert temperature from degree Celsius to Fahrenheit.

## ALGORITHM  
1. Begin the program.  
2. Take input from the user for the temperature in Celsius.  
3. Apply the conversion formula:  
   `fahrenheit = (celsius * 1.8) + 32`  
4. Print the converted temperature in Fahrenheit.  
5. Terminate the program.

## PROGRAM  
```python

cel = float(input("Enter temperature in Celsius: "))
far = (cel * 1.8) + 32
print(f"Celsius = {cel:.2f}")
print(f"Fahrenheit = {far:.2f}")
```

## OUTPUT
![Screenshot 2025-04-29 110041](https://github.com/user-attachments/assets/f1cd570b-64a8-4eb8-8431-fa2f62a3cc65)

## RESULT
Thus, the Python program for converting temperature from Celsius to Fahrenheit has been implemented and executed successfully.


# Experiment No: 1D – Conditional Statements – Printing User Type Based on Choice

## AIM  
To write a Python program to print the type of user based on the user's choice using `if..elif..else` statements.

## ALGORITHM  
1. Start the program.  
2. Accept a numeric input from the user.  
3. Check the input:  
   - If input is `1`, print "Admin".  
   - If input is `2`, print "Editor".  
   - If input is `3`, print "Guest".  
   - Otherwise, print "Wrong entry".  
4. End the program.

## PROGRAM
```python

a = int(input())
if a == 1:
    print('Admin')
elif a == 2:
    print('Editor')
elif a == 3:
    print('Guest')
else:
    print('Wrong entry')
```

## OUTPUT
![image](https://github.com/user-attachments/assets/e26de101-6105-4fb2-bbc0-6488b544b234)

## RESULT
Thus, the Python program for Printing User Type Based on Choice has been Implemented and executed successfully.


# Experiment No: 1e – SEB-Maximum of Three Numbers

## AIM  
To write a Python program to find the maximum between three integer numbers using a conditional expression (Ternary operator).

## ALGORITHM  
1. Begin the program.  
2. Read the three numbers: `a`, `b`, and `c` from the user.  
3. Compare `a`, `b`, and `c` to find the largest number:  
   - If `a` is greater than both `b` and `c`, then `a` is the maximum.  
   - Else, if `b` is greater than both `a` and `c`, then `b` is the maximum.  
   - Otherwise, `c` is the maximum.  
4. Print the maximum value along with the input numbers in the format:  
   `"The maximum of a, b, c is max_num."`  
5. Terminate the program.

## PROGRAM
```python
a = int(input())
b = int(input())
c = int(input())

print('The maximum of', end=' ')
print(a, b, c, sep=', ', end=' ')
print('is', end=' ')

print(a if (a > b and a > c) else (b if b > c else c))

```

## OUTPUT
![image](https://github.com/user-attachments/assets/51b8e6ce-4d73-4ae8-91cc-6200e286d929)

## RESULT
Thus, the Python program to find the maximum between three numbers using a conditional expression has been implemented and executed successfully.
