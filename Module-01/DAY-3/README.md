# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To develop a Java program to check given number is zero or not.

## ALGORITHM :
1.	Start the program.
2.	Declare an integer variable 'num'
3.	Create a Scanner object 'sc' to read input from the user
4.	Read an integer input from the user and store it in 'num'
5.	Check if 'num' is equal to 0:
a.	If true, print "Given number is Zero"
b.	If false, print 'num' followed by " is Non-Zero"
6.	End





## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: Swetha A
RegisterNumber:  212224040343
*/
```

## Sourcecode.java:

```

import java.util.Scanner;

public class Factorial {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        int n = scanner.nextInt(); 
        long factorial = 1; 
        for (int i = 1; i <= n; i++) {
            factorial *= i;
        }

        System.out.println("Factorial of " + n + " is: " + factorial);
    }
}



```





## OUTPUT:
<img width="728" height="348" alt="514199402-302442f5-3d94-46af-a727-f08efcee5def" src="https://github.com/user-attachments/assets/7410422e-a0d6-463f-97e6-cabc82dceb5f" />



## RESULT:
Thus, the Java program to check given number is zero or not was created successfully.


