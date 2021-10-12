#include<stdio.h>
main()
{
	int a=2002, b=2004;
	a=a+b;
	b=a-b;
	a=a-b;
	printf("Before Swapping a=%d b=%d",a,b);
	printf("After swapping a=%d b=%d",b,a);
	return 0;
}
