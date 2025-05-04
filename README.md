# 19CS301-Module7
EX: 7.1 RECURSION
### Aim: To Write a Python Program to find the sum of all digits in a number using recursion
### Algorithm:
STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create a base case for termination of the function. STEP 4: Create a recursive case to calculate the result.

STEP 5: Print the result. STEP 6: Stop.

### Program:
```
def fun(x,n):
    if(n==0):
        return 1
    else:
        return((2**n)*(x**n)+fun(x,n-1))
x=int(input())
n=int(input())
print(fun(x,n))
```
### Output:

![7a](https://github.com/user-attachments/assets/aa64fb4c-1f12-491f-83cc-f790b2c5d6cd)

### Result: Thus, the given program is implemented and executed successfully .
 

EX: 7.2 TYPES OF RECURSIONS
### Aim: To Write a Python program to display first n natural numbers using head recursion 
### Algorithm:

### Program:
```
Step 1: Start
Step 2: Define a recursive function print_natural_numbers(n)
Step 3:
    If n == 0, then
      Return (base case: stop recursion)
Step 4:
    Call print_natural_numbers(n - 1)  ← (recursive call happens first: head recursion)
Step 5:
    Print the value of n
Step 6: End function
Step 7: In the main program:
    a. Read the value of n from the user
    b. Call the function print_natural_numbers(n)
Step 8: End


```
### Output:

![7b](https://github.com/user-attachments/assets/a7cc4ecc-ac17-4e8e-a0ab-0397936ffd3a)


###Result: Thus, the given program is implemented and executed successfully.
 


EX: 7.3 TAYLOR SERIES

###Aim: To python program to evaluate the series using recursion by collecting the x and n values from the user.
### ALGORITHM:
STEP 1: Start.

STEP 2: Create a variable x and n.

STEP 3: Get the values of x and n from user.

STEP 4: Create a base case and recursive case to calculate the result.

STEP 5: Print the result.

STEP 6: Stop.
### Program:
```
def series(x,n):
         if n==0:
            return 1
         else:
            return x**n/n+series(x,n-1)
x = int(input())
n = int(input())
print(series(x,n))
```
### Output:
![image](https://github.com/user-attachments/assets/1d00b1a4-cecb-466f-8593-805f00d27461)

 
### Result: Thus, the given program is implemented and executed successfully .
 

EX: 7.4 Solve by recursion relation

### Aim: To Write a Python Program to find whether a string is a palindrome or not using recursion

### Algorithm:
STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create a base case and recursive case to calculate the result.

STEP 4: Create a variable and get input from user.

STEP 5 : Call the function.

STEP 6: Print the result.

STEP 7: Stop.

### Program:
```
def is_palindrome(word):
      if len(word)<1:
            return True
      else:
            if word[0]==word[-1]:
                 return is_palindrome(word[1:-1])
             else:
                  return False
word = str(input())
if is_palindrome(word)==True:
        print("String is a palindrome")
else:
        print("String is not a palindrome")
```
### Output:
![image](https://github.com/user-attachments/assets/d30ef836-1901-448a-a146-dc905fdc3198)

### Result: Thus, the given program is implemented and executed successfully .
 

