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

