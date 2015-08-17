# factorial
#include<stdio.h>
#include<conio.h>
void main()
{
int a,b,fact=1;
clrscr();
printf("enter a value for factorial \n");
scanf("%d",&a);
for(b=a;b>1;b--)
{
fact=a*(b-1);
a=fact;
printf("Fact is:-%d",fact);
}
getch();
}
