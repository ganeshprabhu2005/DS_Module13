EX3 Implementation of Tower of Hanoi
AIM:
To write a C program to implement Tower of Hanoi

Algorithm
Start the program

Check if n is greater than 0.

Recursively move n-1 disks from source (x) to auxiliary (z) using destination (y).

Print the move of the n-th disk from source (x) to destination (y).

Recursively move n-1 disks from auxiliary (z) to destination (y) using source (x)

The function is called initially with TOH(n, 'A', 'B', 'C') where 'A', 'B', and 'C' are the rods
End the program.

Program:
/*
Program to implement Tower of Hanoi

Developed by: GANESH PRABHU J

RegisterNumber:  212223220023

*/
```
#include<stdio.h> 
void TOH(int n,char x,char y,char z) 
{ 
if(n>0) 
{ 
TOH(n-1,x,z,y); 
printf("%c to %c",x,y); 
printf("\n"); 
TOH(n-1,z,y,x); 
} 
} 
int main() 
{ 
int n=2; 
TOH(n,'A','B','C'); 
}
```
Output:

<img width="390" height="242" alt="437888780-bd342b8d-2fb3-4620-98fa-68ab404ab030" src="https://github.com/user-attachments/assets/0c6cec22-cf19-4312-9f79-5b3d946cb8d9" />


Result:
Thus, the C program to implement Tower of Hanoi using recursion is implemented successfully.
