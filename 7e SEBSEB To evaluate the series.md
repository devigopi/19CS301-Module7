7(e) EX:SEB To evaluate the series
AIM:7e
  Write a Python Program to evaluate the series:  1/1!+1/2!+1/3!+....+1/n!  using recursion.
Algorithm:
Step 1:Start
Step 2:Input the value of n
Step 3:Define a recursive function factorial(k) to compute factorial of k
  If k is 0 or 1, return 1
  Else return k * factorial(k - 1)
Step 4:Define a recursive function series(n) to compute the sum of the series
  If n == 1, return 1 / factorial(1)
  Else return 1 / factorial(n) + series(n - 1)
Step 5:Call the series(n) function and print the result
Step 6:End

Program:
    ```
def factorial(n):
    if(n==0):
        return 1
    return(n*factorial(n-1))
        
Limit=int(input())
sum=0
for i in range(1,Limit+1):
    sum=sum+(1/factorial(i))
print(sum)
```
Output:

![Seb 7e](https://github.com/user-attachments/assets/0e54b392-2f47-4d46-bc36-5080ac6c3467)

Result:
   Thus, the given program is implemented and executed successfully .





