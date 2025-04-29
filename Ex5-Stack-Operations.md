# Ex5 Stack Operations
## DATE:
## AIM:
To write a C function to perform push and pop operation of the stack in the infix to postfix conversion.

## Algorithm
### Push(x)
1.Increment top by 1.

2.Place x at stack[top].

### Pop()
1.Retrieve the element at stack[top].

2.Decrement top by 1.

3.Return the retrieved element.

  

## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: Meyyappan T
RegisterNumber:  212223240086
*/


#include<stdio.h>

char stack[100];
int top = -1;

void push(char x)
{
   stack[++top]=x;
}

char pop()
{

   return stack[top--];
}


```

## Output:

![image](https://github.com/user-attachments/assets/a2998db0-c9ae-4280-94d4-542fc3b4e413)


## Result:
Thus the C program to perform push and pop operation of the stack in the infix to postfix conversion is implemented successfully.
