#include<stdio.h>
#include<conio.h>
 void main ()
 {
     float a,b,c;
     char ch;
     printf ("enter first number:");
     scanf("%f",&a);
     printf("enter user to perform operation:");
     scanf(" %c",&ch);
     printf("Enter second number:");
     scanf("%f",&b);
     switch(ch)
     {
         case '+': c=a+b;
         printf("output=%f",c);
         break;
         case '-': c=a-b;
         printf("output=F",c);
         break;
         case '*': c=a*b;
         printf("output=%f",c);
         break;
         case '/': c=a/b;
         printf("output=%f",c);
         break;
         default: printf("invalid operation");
         break;
     }
     getch();
 }
