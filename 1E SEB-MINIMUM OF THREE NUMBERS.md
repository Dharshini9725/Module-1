# Experiment No: 1e – SEB-Minimum of Three Numbers

## AIM  
To write a Python program to find the minimum between three integer numbers using a conditional expression (Ternary operator).

## ALGORITHM  
1. Begin the program.  
2. Read the three numbers: `num1`, `num2`, and `num3` from the user.  
3. Compare `num1`, `num2`, and `num3` to find the smallest number:  
   - If `num1` is less than or equal to both `num2` and `num3`, then `num1` is the minimum.  
   - Else, if `num2` is less than or equal to both `num1` and `num3`, then `num2` is the minimum.  
   - Otherwise, `num3` is the minimum.  
4. Print the minimum value along with the input numbers in the format:  
   `"The minimum of num1, num2, num3 is min_num."`  
5. Terminate the program.

## PROGRAM
```python
# Reg.No-212223060050
# Name-Dharshini V S

a=int(input())
b=int(input())
c=int(input())
min=a
if(b<a) and (b<c):
    min=b
elif(c<a) and (c<b):
    min=c
print(f'The minimum of {a}, {b}, {c} is {min}')
```

## OUTPUT
<img width="1259" height="440" alt="Screenshot 2025-08-31 175434" src="https://github.com/user-attachments/assets/d82143c6-e27e-483b-8a49-9068cddd3dce" />


## RESULT
Thus a Python program to find the minimum between three integer numbers using a conditional expression has been implemented and executed successfully.
