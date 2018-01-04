# to-becoming-a-super-engerneer
it is what I learn in four years.
/*计算数组中字符和数字的个数*/
#include<stdio.h>
int main()
{
int m,n;
char a[80];
printf("enter your number:");
while((a[n]=getchar())!='\n')
   n++;
   a[n]='\0';
for(n=0;a[n]!='\n';n++)
if(a[n]>='0')
   m++;
printf("the number is%d\nthe character is%d",m,n-m);
return 0;
}
