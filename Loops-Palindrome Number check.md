## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
a=int(input())
i=a
sum=0
while(i!=0):
      rev=i%10
      sum=sum*10+rev
      i//=10
if (a == sum):
      print("the number is a palindrome.")
else:
      print("the number is not a palindrome.")
```
## Output
![alt text](<Screenshot (48).png>)
## Result
The Python program that checks whether a given number is a **palindrome** using loops is executed successfully
