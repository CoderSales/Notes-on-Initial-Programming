# Notes-on-Initial-Programming

## Description
Notes-on-Initial-Programming

## Table of Contents of Brightspace Module

[Lecture 1](https://learn.ul.ie/d2l/le/lessons/10840/topics/458147)

[Lecture 2 (not found)](https://learn.ul.ie/d2l/le/lessons/10840/topics/458507)

[Lecture 3](https://learn.ul.ie/d2l/le/lessons/10840/topics/463731)

[Lecture 4](https://learn.ul.ie/d2l/le/lessons/10840/topics/480279)

____

[Lab Week 5](https://learn.ul.ie/d2l/le/lessons/10840/topics/500828)

no later content than this on 2023-10-16-at-1529h

## Content

### Week-6

#### Lecture-Week-6

##### Digital Ocean

Let’s look at the available format specifiers available for printf:

%c character

%d decimal (integer) number (base 10)

%e exponential floating-point number

%f floating-point number

%i integer (base 10)

%o octal number (base 8)

%s String

%u unsigned decimal (integer) number

%x number in hexadecimal (base 16)

%t formats date/time

%% print a percent sign

\% print a percent sign

###### ChatGPT3_5

In the System.out.printf method in Java (and similar formatting in other programming languages), the % symbol is used to indicate a placeholder for a value to be inserted into the string being formatted. The characters following % specify the formatting for the value 

that will be inserted.

In the example "%9.7f":

% indicates the start of the formatting specifier.

9 specifies the minimum width of the field where the value will be inserted. In this case, it's saying that the minimum width is 9 characters. If the inserted value is less than 9 characters wide, it will be padded with spaces to the left.

.7 specifies the precision for floating-point numbers. It indicates that 7 decimal places should be shown.

f specifies that the value being inserted should be formatted as a floating-point number.

So, in summary, %9.7f is a formatting specifier for a floating-point number with a minimum width of 9 characters and 7 decimal places of precision.


```java
public class PrintPi {
    public static void main(String[] args) {
        double piValue = Math.PI;
        System.out.printf("Value of PI to 7 dec is %9.7f\n", piValue);
    }
}

```

```java
System.out.printf("Value of PI to 4 dec is %9.4f\n", Math.PI);
```

```java
System.out.printf("Value of PI to 2 dec is %-9.2f\n", Math.PI);
```

## Refrerences

### Printf

[geeksforgeeks Printf](https://www.geeksforgeeks.org/formatted-output-in-java/)

[digital ocean Printf](https://www.digitalocean.com/community/tutorials/java-printf-method)

[ASCII Table](https://www.asciitable.com/)
