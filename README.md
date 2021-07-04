# grade-calculatuion-program-in-c
#include<stdio.h>
int main()
{
	printf("Enter your marks:");
	int marks=0;
	scanf("%d",&marks);
	{
		if(marks<=0 || marks>100)
	
	{
		printf("Invalid marks");
		return 0;
	}
	}
	if(marks>=85 && marks<=100)
	{
		printf("Grade A");
	}
	else if(marks>=70)
	{
		printf("Grade B");
	}
	else if(marks>=55)
	{
		printf("Grade C");
	
	}
	else if(marks>=40)
	{
		printf("Grade D");
	
	}
	else
	{
		printf("Grade F");
		return 0;
	}
}
