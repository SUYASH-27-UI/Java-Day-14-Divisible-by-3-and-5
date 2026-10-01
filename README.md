# Java-Day-14-Divisible-by-3-and-5
# Java Day 14 - Divisible by 3 and 5

This program checks whether a number entered by the user is divisible by both 3 and 5.

## Example

Input:

```text id="j14input"
30
```

Output:

```text id="j14out"
30 is divisible by both 3 and 5.
```

## Concepts Used

* Scanner
* User input
* `if-else`
* Modulus operator `%`
* AND operator `&&`
* Comparison operator `==`

## How It Works

1. The program creates a `Scanner` object.
2. The user enters a number.
3. The program checks whether the number is divisible by 3.
4. It also checks whether the number is divisible by 5.
5. The `&&` operator requires both conditions to be true.
6. If both conditions are true, the program displays that the number is divisible by both 3 and 5.
7. Otherwise, it displays that the number is not divisible by both.

## Java Code

```java id="j14fullcode"
import java.util.Scanner;

public class Main
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a number: ");
        int number = sc.nextInt();

        if (number % 3 == 0 && number % 5 == 0)
        {
            System.out.println(number + " is divisible by both 3 and 5.");
        }
        else
        {
            System.out.println(number + " is not divisible by both 3 and 5.");
        }

        sc.close();
    }
}
```

## Output

```text id="j14output2"
Enter a number: 30
30 is divisible by both 3 and 5.
```

## Goal

The goal of this project is to practice the modulus operator and the `&&` AND operator by checking multiple conditions in Java.
