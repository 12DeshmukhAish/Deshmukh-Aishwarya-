# Deshmukh-Aishwarya-
//Code of Binary search
#include<stdio.h>
Void main {
int i, first,last, middle,n, search,a[30];
printf("\n enter size of array");
scanf("%d",&n);
printf("enter %d integers\n",n);
for(i=0;i<n;i++)
scanf("%d",&a[i]);
printf("\ enter the value of search");
scanf("%d",&search);
first =0;
last=n-1;
middle =(first + last)/2;
while(first<=last)
{
if(a[middle]<search)
first = middle +1;
else if(a[middle]==search)
{
printf("%d is found at location%d",search, middle+1);
}



