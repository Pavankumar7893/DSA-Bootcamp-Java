# [Video Link](https://youtu.be/TAtrPoaJ7gc)

## Write Java programs for the following:

1. Write a program to print whether a number is even or odd, also take
input from the user.




CODE:
import java.util.*;
public class EvenOdd {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Please enter the number to check Even or Odd ");
        int number = sc.nextInt();
        if(number%2==0){
            System.out.println("The given nuber is EVEN");
        }
        else{
            System.out.println("The given nuber is ODD");

        }
        sc.close();
    }
}



3. Take name as input and print a greeting message for that particular name.
  CODE:


import java.util.*;
public class Greet {
    public static void main(String[] args) {
    Scanner sc = new Scanner(System.in);
    System.out.println("Please enter your name:");
    String name = sc.nextLine();
    System.out.println("Welcome Mr/Ms "+name+"!");
    }
}




5. Write a program to input principal, time, and rate (P, T, R) from the user and
find Simple Interest.


CODE:


import java.util.*;
public class SimpleIntrest {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the Principle");
        Double principle = sc.nextDouble();
        System.out.println("Enter the Time");
        int Time = sc.nextInt();
        System.out.println("Enter the Rate");
        int Rate = sc.nextInt();
        Double SimpleInterest = (principle*Time*Rate)/100;
        System.out.println("The simple Interest is: "+SimpleInterest);




    }
}




7. Take in two numbers and an operator (+, -, *, /) and calculate the value.
(Use if conditions)

9. Take 2 numbers as input and print the largest number.
10. Input currency in rupees and output in USD.
11. To calculate Fibonacci Series up to n numbers.
12. To find out whether the given String is Palindrome or not.
13. To find Armstrong Number between two given number.

