# EXP -3 Java program to find the number of day in a month
## Aim:-
to write a java program to find the number of day in a month.

## Procedure:-
### Step 1:
Import the required packages.

### Step 2:
Get the month number from the user.

### Step 3:
Assign number of days based on month number using switch statement.

### Step 4:
Display number of days in the month.

### Step 5:
Stop the execution.

### Program:-
#### Developed By : Kirupanandhan T
#### Register Number : 212221230051
```java
import java.util.Scanner;
public class DaysInMonth
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        System.out.print("Enter the Month number: ");
        int mon_no=sc.nextInt();
        int days=0;
        switch(mon_no)
        {
            case 1:
                days=31;
                break;
            case 2:
                days=28;
                break;
            case 3:
                days=31;
                break;
            case 4:
                days=30;
                break;
            case 5:
                days=31;
                break;
            case 6:
                days=30;
                break;
            case 7:
                days=31;
                break;
            case 8:
                days=31;
                break;
            case 9:
                days=30;
                break;
            case 10:
                days=31;
                break;
            case 11:
                days=30;
                break;
            case 12:
                days=31;
                break;
        }
        System.out.println("Number of days in the month is "+days);
    }
}
```
## Output:-
![image](https://github.com/Kirupanandhan/Java-program-to-fins-the-number-of-day-in-a-month/assets/94386222/9c6b968f-ded0-4ef5-b7a7-9234df789f1c)

## Result:-
A java program to find the number of day in a month has been executed successfully.
