#include<stdio.h>
#include<conio.h>
void main()
{
void swap(int* ,int* );
int a,b;
printf("Enter 2 numbers");
scanf("%d%d",&a,&b);
swap(&a,&b);
printf("%d%d",a,b);
}
void swap(int*x,int*y)
{
int temp;
temp=*x;
*x=*y;
*y=temp;
}
