# Python Basics
## Computer programming and Python Fundamentals 
#### Function : 
Part of our code that is used to cause an affect or evaluate a value
- For example : ```print```
#### Function Execution :
- checks the function name
- checks the arguments passed
- jumps into the function
- executes the function
- returns to the code
- resumes the execution
#### Literals :
A literal is a data itself which values are determined by the literals itself.
#### Literal Types:
![image](https://github.com/user-attachments/assets/89b12b39-f127-4afd-9bcf-01429a61850f)
#### Operators :
![WhatsApp Image 2025-02-11 at 11 56 04_b6344d69](https://github.com/user-attachments/assets/1f6f8abc-b6dd-43d3-9a18-d909200804be)
- ```Addition (+)``` : Addition of the number
  - Example : ```5 + 3 = 8```
- ```Subtraction (-)``` : Subtraction of the number
  - Example : ```5 - 3 = 2```
- ```Mutliplication (*)``` : Multiplies two numbers
  - Example : ```5 * 2 = 10```
- ```Division (/)``` : Divides first number by second (returns float)
  - Example : ```5 / 2 → 2.5```
- ```Floor Division (//) ``` : Divides and rounds down to nearest integer
  - Example : ```5 // 2 → 2```
- ```Modulo (%) ```	: Returns remainder of division
  - Example : ```5 % 2 → 1```
- ```Exponentiation (**)``` : Raises first number to the power of second
  - Example : ```5 ** 2 → 25```      
#### Priority of the operators :
![WhatsApp Image 2025-02-11 at 12 07 14_4648ea30](https://github.com/user-attachments/assets/b4063235-168a-4e04-a256-6c85e1ebe74d)
#### Variables 
- Variables allow to save values
- A variable has a valid name (letters, digits, underscore, not a reserved keyword)
- Python is dynamically typed: variables can be redeclared
- We can use shortcut operators in order to cleanly redeclare a variable. 
#### ```input()```
- Prompts the user to input some data or value in the console when we try to execute
```bash
>>> input("How old are you ?")
    How old are you ? 22
  ```
- Always returns a string
- A program that doesn't have any ```input()``` funtion is called as ```deaf program```
```bash
>>> favorite_color = input("What is your favorite color ?")
    what is your favorite color ? blue
>>> print ("My favorite color is" + favorite_color)
    My favorite color is blue
```
#### String Operations:
- we can use ```+``` in order to ```concatenate``` two strings.
- we can use ```*``` in order to repeat a string a several amount of times.
- With the ```str``` function, you can use type-cast a number into a string.
```bash
>>> cost_of_apple = 2
>>> amount_of_apples = input("How many apples do you want ?")
    How many apple do you want ? 10
>>> total_sum = cost_of_apple * int(amount_of_apples)
>>> print("you have to pay: " + str(total_sum))
    you have to pay: 20
```
#### Comparison Operators
- ```Equal (==)```
- ```Not Equal (!=)```
- ```Greater than (>)```
- ```Greater than or equal to (>=)```
- ```Less than (<)```
- ```Less than or equal to  (<=)```

- These operators returns ths boolen values such as True or False as the result.

#### Conditonal Statements :
```if-else``` condition :
```bash
if condition 
   print("This condition is true")
else
   print("This condition is false")
```
```elif``` condition :
```bash
if condition
   print ("This condition is true")
elif condition
   print ("Only this condition will be true")
else
   print( "This condition is true")
```
##### Example :
```bash
x = 0
a = 6
b = 6

if a > 0:  # (1) Check if a is greater than 0
    if b < 0:  # (2) Check if b is less than 0
        x = x + 6  
    elif a > 6:  # (3) Check if a is greater than 6
        x = x + 5
    else:  # (4) If neither condition (b < 0 or a > 6) is met
        x = x + 4
else:  # (5) If a is NOT greater than 0
    x = x + 3

print(x)  # (6) Output the final value of x
```
Things need to be observed here :
- a = 6 > 0, we enter the first if block.
- Since b = 6 is not negative, we skip the if b < 0 condition.
- Since a = 6 is not greater than 6, we skip the elif a > 6 condition.
- We enter the else block, adding 4 to x.
- The final printed value of x is 4.

#### Note :
- In Python, the following values are considered falsy:
  - 0
  - None
  - False
  - '' (empty string)
  - [] (empty list)
  - {} (empty dictionary)
  - () (empty tuple)
- Everything else is considered truthy, including:
  - Non-zero numbers (5, 10)
  - Non-empty tuples ((5,10))
  - Non-empty lists ([5,10])
  - Non-empty strings ('hello')
#### For loop :
- ```if/else``` statements allow us to conditionally run code
- ```while``` loop makes it possible to repetitively execute code based on a certain code
- We can execute code for each item in a sequence with a ```for...in``` loop.
#### when writing loops (```for``` and ```while```) with conditions, the basic structure follows this pattern:
- ```for``` loop with conditions
```bash
for variable in sequence:
    if condition:  # Check condition
        # Do something
    else:
        # Do something else
```
- ```while``` loop with conditions
```bash
while condition:
    # Code block
    if another_condition:
        break  # Stops the loop
    elif different_condition:
        continue  # Skips the rest of the iteration
```
#### Operators :
![image](https://github.com/user-attachments/assets/1676d61a-0469-4a7e-97be-509135db7e6f)
#### Operators:
- Logical operators ```and not``` and ```or``` return boolean values based on the passes values
- Bitwise operators ```& (Conjunction), | (Disjunction), ^ (Exclusive) and ~ (Negation) ``` allows us to manipulate single bits of     data, return ```0 or 1``` based on the value of the bits that are used.
- Bit shifting can be done with the ```<< (Bit left shifting) and >> (Bit right shifting) ``` operators.
#### List :

```bash
                   0       1          3
>>> countries = ["USA", "India", "Cannada"]
                  -3       -2       -1
```
##### Python list slicing :
```list[start:stop:step:]```
- start : The index where slicing begins [default by 0]
- stop : The index where slicing stops
- step : The interval between elements [default is 1]
