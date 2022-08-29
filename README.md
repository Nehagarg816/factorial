# factorial
This is a program for finding factorial using functions in the type of take something return something.
#include<stdio.h>
#include<conio.h>
int factorial(int a);

void main()
{
	int s,a;
	printf("Enter one number a:");
	scanf("%d",&a);
	s=factorial(a);
	printf("Factorial of a is %d",s);
}
int factorial(int x)
{
	int i,fact=1;
	for(i=1;i<=x;i++)
	{
		fact=fact*i;
	}
	return(fact);
}
