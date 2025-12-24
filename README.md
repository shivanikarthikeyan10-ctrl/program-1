C-Module 1
EX_NO-01)a)-Datatypes-Operators
Date: 24/12/25
Name: SHIVANI K
Register Number: 25013585


AIM:
Write a C program to read a float value from the user and to display the same value.

ALGORITHM:
Start the program.
Declare a float variable to store the input value.
Read the float value from the user using the scanf function.
Print the float value using the printf function with two decimal places (%.2f).
End the program.


PROGRAM:
```
#include <stdio.h>
int main()
{
    float num;
    scanf("%f",&num);
    printf("%.2f",num);
    return 0;
}
```
OUTPUT:


![WhatsApp Image 2025-12-24 at 9 56 07 PM](https://github.com/user-attachments/assets/734ad1e7-e574-4a11-aba4-29197d9cc3c0)


RESULT:

  Thus the program to find the float value from the user and to display the same value runs successfully.















Program-1-b
C-Module 1
EX_NO-01)b)-Conditional Statements

AIM:

Write a C program to read A values and check whether the value is greater than and equal to 100.

ALGORITHM:
Start the program.

Declare an integer variable to store the input value.

Read the integer value from the user using the scanf function.

Check if the value is greater than or equal to 100.

a. If true, print "The Value is greater than or equal to 100".

b. If false, do nothing (or skip printing).

End the program.
```

PROGRAM:
#include <stdio.h>
int main()
{
    int num;
    scanf("%d",&num);
    if(num>=100){printf(
        "The Value is greater than or equal to 100");}
    
 return 0;   
}
```
OUTPUT:

![WhatsApp Image 2025-12-24 at 10 21 14 PM](https://github.com/user-attachments/assets/455ac337-172a-4b60-bb16-36bf1df812f5)





RESULT:


Thus the program to read A values and check whether the value is greater than and equal to 100 has been executed successfully.










Program-1-c
C-Module 1
EX_NO-01)c)-Operators & Expressions



AIM:


Write a program to find principle amount based on simple interest, time & rate of interest.

ALGORITHM:

Start the program.

Declare three float variables to store simple interest, time, and rate of interest.

Read the values of simple interest, time, and rate from the user using the scanf function.

Declare a float variable to store the principle amount.

Calculate the principle amount using the formula:

Principle = (Simple Interest) / (Time * Rate) * 100
Print the principle amount using the printf function with two decimal places.

End the program.

PROGRAM:

```
#include <stdio.h>
int main()
{
    float sint;
    float time;
    float rate;
    scanf("%f %f %f",&sint,&time,&rate);
    float pri;
    pri=sint/(time*rate);
    pri=pri*100;
    printf("Principle amount is = %.2f",pri);
    return 0;
}
```


OUTPUT:


![WhatsApp Image 2025-12-24 at 10 26 49 PM](https://github.com/user-attachments/assets/33feb4b0-8af4-4318-a90c-71ea13daa72b)





RESULT:


Thus the program to find principle amount based on simple interest, time & rate of interest has been executed successfully.














Program-1-d
C-Module 1
EX_NO-01)d)-Conditional Statements


AIM:

Write a C program to read a, b values and check whether a equal to b.

ALGORITHM:

Start the program.

Declare two integer variables to store the input values.

Read the two integer values from the user using the scanf function.

Check if the first value is equal to the second value.

a. If true, print "a is equal to b".

b. If false, do nothing (or skip printing).

End the program.

PROGRAM:
```
#include <stdio.h>
int main()
{
int a,b;
scanf("%d %d",&a,&b);
if(a==b)
printf("a is equal to b");
 return 0;   
}
```


OUTPUT:



![WhatsApp Image 2025-12-24 at 10 30 31 PM](https://github.com/user-attachments/assets/eed97cef-5a69-413b-9825-3997fcf54766)



RESULT:


Thus the program to read a, b values and check whether a equal to b has been executed successfully.




Program-1-e
C-Module 1
EX_NO-01)e)-Datatypes & Operators



AIM:

Write a C program to find the ASCII value of a given character.

ALGORITHM:


Start the program.
Declare a character variable to store the input character.
Read the character from the user using the scanf function.
Print the ASCII value of the character using the printf function.
End the program.


PROGRAM:

```
#include <stdio.h>
int main()
{
    char ch;
    scanf("%c",&ch);
    printf("ASCII value of %c is %d",ch,ch);
    return 0;
}
```
OUTPUT:


![WhatsApp Image 2025-12-24 at 10 32 29 PM](https://github.com/user-attachments/assets/c0e95310-3e0b-4143-bfbf-51bf6e877d1b)


RESULT:


Thus the program to find the ASCII value of a given character has been executed successfully.
