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
