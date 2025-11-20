# EX3 Write a program to count the number of digits in an integer.
## DATE:13/08/2025
## AIM:
To write a  java program to count the number of digits in an integer.

## Algorithm
1. Start and read an integer n from the user.
2. Initialize a variable count = 0.
3. If n == 0, set count = 1 (since 0 has 1 digit).
4. Otherwise, repeat while n ≠ 0:
  • Divide n by 10
  • Increment count
5. Display "Number of digits: " + count and stop.  

## Program:
```
/*
Program to to count the number of digits in an integer
Developed by: GANESH PRABHU J
RegisterNumber: 212223220023

import java.util.Scanner;

public class CountDigits {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n=sc.nextInt();
        int count=0;
        if(n==0){
            count=1;
        }
        else{
             while(n!=0){
                 n=n/10;
                 count++;
             }
        }
        System.out.println("Number of digits: " + count);
    }
}
 
*/
```

## Output:
<img width="964" height="339" alt="image" src="https://github.com/user-attachments/assets/401a26e4-d61d-4e28-953d-08239c4ece25" />




## Result:
Thus, the Java program to to count the number of digits in an integer is implemented successfully.
