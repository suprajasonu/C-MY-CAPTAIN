#include<stdio.h>
void main()
{
int n1,n2,temp;
printf("enter  the first number");
scanf("%d",&n1);
printf("\nenter  the second number");
scanf("%d",&n2);
temp=n1;
n1=n2;
n2=temp;
printf("\nn1 after swapping %d",n1);
printf("\nn2 after swapping %d",n2);
}
