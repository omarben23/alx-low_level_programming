First task :

#include <stdlib.h>
#include <time.h>
#include <stdio.h>
/* more headers goes there */

/* betty style doc for function main goes there *e */
/**
 * main - Entry point
 *
 * Return: Always 0 (success)
 */
int main(void)
{
        int n;

        srand(time(0));
        n = rand() - RAND_MAX / 2;
        /* your code goes there */
        if (n > 0)
                printf("%d is positive\n", n);
        else if (n == 0)
                printf("%d is zero\n", n);
        else
                printf("%d is negative\n", n);
        return (0);
}
 
: 0. Positive anything is better than negative nothing
mandatory
This program will assign a random number to the variable n each time it is executed. Complete the source code in order to print whether the number stored in the variable n is positive or negative.

You can find the source code here
The variable n will store a different value every time you will run this program
You don’t have to understand what rand, srand, RAND_MAX do. Please do not touch this code
The output of the program should be:
The number, followed by
if the number is greater than 0: is positive
if the number is 0: is zero
if the number is less than 0: is negative
followed by a new line

-------- second task : 

#include <stdlib.h>
#include <time.h>
#include <stdio.h>
/* more headers goes there */

/* betty style doc for function main goes there */
/**
 *main - Entry point
 * Return: 0 (success)
 */
int main(void)
{
        int n;
        int m;


        srand(time(0));
        n = rand() - RAND_MAX / 2;
        /* your code goes there */

        m = n % 10;
        if (m > 5)
                printf("Last digit of %d is %d and is greater than 5\n", n, m);
        if (m == 0)
                printf("Last digit of %d is %d and is 0\n", n, m);
        if (m < 6 && m != 0)
                printf("Last digit of %d is %d and is less than 6 and not 0\n", n, m);
        return (0);
}

;
This program will assign a random number to the variable n each time it is executed. Complete the source code in order to print the last digit of the number stored in the variable n.

You can find the source code here
The variable n will store a different value every time you run this program
You don’t have to understand what rand, srand, and RAND_MAX do. Please do not touch this code
The output of the program should be:
The string Last digit of, followed by
n, followed by
the string is, followed by
if the last digit of n is greater than 5: the string and is greater than 5
if the last digit of n is 0: the string and is 0
if the last digit of n is less than 6 and not 0: the string and is less than 6 and not 0

------------------ 
third task: 

#include <stdio.h>
/**
 * main - Entry point
 *
 * Return: 0 (success)
 */
int main(void)
{
        char c;

        c = 'a';
        while
                (c <= 'z') {
                        putchar(c);
                        c++;
                }
        putchar('\n');
        return (0);
}
:

Write a program that prints the alphabet in lowercase, followed by a new line.

You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
All your code should be in the main function
You can only use putchar twice in your code

----------------------
fourth task 

#include <stdio.h>
/**
 * main - Entry point
 *
 * Return: 0 (success)
 */
int main(void)
{
        char c;

        char d;

        c = 'a';
        d = 'A';
        while
                (c <= 'z') {
                        putchar(c);
                        c++;
                }
        while
                (d <= 'Z') {
                        putchar(d);
                        d++;
                }
        putchar('\n');
        return (0);
}

:
Write a program that prints the alphabet in lowercase, and then in uppercase, followed by a new line.

You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
All your code should be in the main function
You can only use putchar three times in your code

--------------------------------
fifth task :

#include <stdio.h>
/**
 * main - Entry point
 *
 * Return: 0 (success)
 */
int main(void)
{
        char c;

        c = 'a';
        while
                (c <= 'z') {
                        if ((c != 'q' && c != 'e') && c <= 'z')
                                putchar(c);
                        c++;
                }
        putchar('\n');
        return (0);
}

:

Write a program that prints the alphabet in lowercase, followed by a new line.

Print all the letters except q and e
You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
All your code should be in the main function
You can only use putchar twice in your code

--------------------------
sixth task: 

#include <stdio.h>
/**
 * main - Entry point
 *
 * Return: 0 (success)
 */
int main(void)
{
        int a;

        for (a = 0; a <= 9; a++)
                printf("%d", a);
        putchar('\n');
        return (0);
}

: 

Write a program that prints all single digit numbers of base 10 starting from 0, followed by a new line.

All your code should be in the main function

-------------------------
seventh task : 

#include <stdio.h>
/**
 * main - Entry point
 *
 * Return: 0 (success)
 */
int main(void)
{
        int c;

        c = 0;
        while
                (c < 10) {
                        putchar(c + '0');
                        c++;
                }
        putchar('\n');
        return (0);
}
 : 

Write a program that prints all single digit numbers of base 10 starting from 0, followed by a new line.

You are not allowed to use any variable of type char
You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
You can only use putchar twice in your code
All your code should be in the main function

-----------------
eigtth task : 

#include <stdio.h>
/**
 * main - Entry point
 *
 * Return: 0 (success)
 */
int main(void)
{
        char c;

        c = 'z';
        while
                (c >= 'a') {
                        putchar(c);
                        c--;
                }
        putchar('\n');
        return (0);
}
: 

Write a program that prints the lowercase alphabet in reverse, followed by a new line.

You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
All your code should be in the main function
You can only use putchar twice in your code

------------------------- 
nineth task : 

~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
-- INSERT --                                                                                                                                                                                                   3,1   
