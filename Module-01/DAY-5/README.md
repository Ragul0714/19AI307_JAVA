# Ex.No:1(E)  STATIC VARIABLE

## AIM:
To write a Java program to print student details (name and age), where age is the same for all students. Use a static variable to represent the age and demonstrate its use in accessing a shared value across all class objects

## ALGORITHM :
1.	Start the program.
2.	Create a class named Student.
3.	Declare a static variable age in the Student class.
4.	Declare an instance variable name.
5.	Create a constructor to initialize the student's name.
6.	Define a method displayDetails() to print the student's name and age.
7.	In the main method:
I.	Assign a value to the static variable age.
II.	Create multiple Student objects with different names.
III.	Call the displayDetails() method for each student.
8.	End the program.



## PROGRAM:
 ```
/*
Program to implement a Static Variable using Java
Developed by: Swetha A
RegisterNumber:  212224040343
*/
```

## Sourcecode.java:


```

import java.util.Scanner;

public class ReverseString {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        String input = sc.nextLine();

        String reversed = "";
        for (int i = input.length() - 1; i >= 0; i--) {
            reversed += input.charAt(i);
        }

        System.out.println("Reversed string: " + reversed);
        sc.close();
    }
}



```




## OUTPUT:

<img width="695" height="355" alt="514207258-110b52e2-3378-4756-85e7-ecb58ad8f1ea" src="https://github.com/user-attachments/assets/9504dd54-387c-4920-a032-f25bac63eac4" />



## RESULT:
Thus, the Java program for the concept of using a static variable for shared data was correctly implemented and verified successfully. 

