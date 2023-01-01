## Variables
```
age = 20 

print("age")
print(age)
```
#### The result of print("age") is age because you called for the string age. The result of print(age) is 20 because you called for the value of the variable, age, which is 20. 
<br/>

## Input
```
name = input("What is your name? ")
print("Hello" + name)
```
#### The string in the parenthesis next to the input function is displayed and the value that is inputted is inserted into the variable given, which is name, in this case. 
<br/>

## Type Conversion
```
birth_year = input("Enter your birth year: ")
age = 2020 - birth_year
print(age)
```
#### The reason why this line of code is invalid is because the value that is inserted inplace of the input function is a string. However, 2020 is a integer, which makes it impossible to compare an integer and a string. 
```
birth_year = input("Enter your birth year: ")
age = 2020 - int(birth_year)
print(age)
```
#### You need to change the value of birth_year from a string to an integer with the function, int(birth_year). 
```
int()
float()
bool()
str()
```
#### This is a list of some other functions you can use for type conversion. 
<br/>

## Strings 
```
course = 'Python for Beginners'

print(course.upper())
print(course.lower())
print(course.find('y'))
print(course.replace('for', '4'))
print('Python' in course)
```
#### course.upper() switches all letters in course to uppercase. 
#### course.lower() switches all letters in course to lowercase.
#### course.find('y') returns the index of the letter 'y', in this case 1. The index of the first letter is 0. 
#### course.replace('for', '4') replaces 'for' to '4', thus returning the string 'Python 4 Beginners'.
#### ('Python' in course) checks whether there is a string 'Python', and returns a Boolean value, in this case, true.
<br/>

## Arithmetic Operators
```
+
-
*
/
//
%
**
x += 3
```
#### + represents addition.
#### - represents subtraction.
#### * represents multiplication.
#### / represents division.
#### // represents division, but returns an integer.
#### % returns the remainder after dividing.
#### ** represents the power of.
#### x += 3 means x = x + 3. 
<br/>

## Operator Precedence
```
x = 10 + 3 * 2
```
#### Multiplication and subtraction comes before addition and subtraction. The equation above returns a value of 16. 
<br/>

## Comparison Operators
``` 
x > 3
x < 3
x == 3 
x != 3 
x >= 3 
x <= 3 
```
#### The comparison operators above return a boolean value of true or false. 
<br/>

## Logical Operators
```
price = 5 

print(price > 10 and price < 30)
print(price > 10 or price < 30)
print(not price > 10)
```
#### and requires both comparisons to return true to be true. 
#### or requires just one of the comparisons to return true to be true.
#### not flips the value of the comparison. 
<br/>

## If Statements 
```
if temperature > 30: 
    print("It's a hot day!")
elif temperature > 10: 
    print("It's pretty chill")
else:
    print("It's cold")
print("Done")
```
#### if gives a condition to fulfill. If the condition is fulfilled, the indented code below is run. 
#### elif means else if, which means the if condition is false but the elif condition is true for the indented code to run. 
#### else means everything else, which means the if condition is false, and the elif condition is false as well for the code to run. 


