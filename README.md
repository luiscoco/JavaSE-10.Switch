# JavaSE-10.Switch

In Java, the switch statement is used to select one of many code blocks to be executed. 

It's often used as an alternative to a series of if-else statements when you have multiple possible conditions to check.

Here's a simple example:

```java
public class SwitchExample {
    public static void main(String[] args) {
        int dayOfWeek = 3;

        switch(dayOfWeek) {
            case 1:
                System.out.println("It's Monday!");
                break;
            case 2:
                System.out.println("It's Tuesday!");
                break;
            case 3:
                System.out.println("It's Wednesday!");
                break;
            case 4:
                System.out.println("It's Thursday!");
                break;
            case 5:
                System.out.println("It's Friday!");
                break;
            case 6:
                System.out.println("It's Saturday!");
                break;
            case 7:
                System.out.println("It's Sunday!");
                break;
            default:
                System.out.println("Invalid day!");
        }
    }
}
```

In this example, the variable dayOfWeek is checked against different cases, and the corresponding block of code is executed based on the match. 

The break statement is used to exit the switch statement once a match is found.

The default case is optional and is executed if none of the cases match. It's similar to the else statement in an if-else structure.

Keep in mind that switch statements can only be used with certain data types in Java, like int, char, enum, etc. 

Also, each case must end with a break statement to avoid "falling through" to the next case unintentionally.

