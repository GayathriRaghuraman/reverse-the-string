# reverse-the-string
#include<stdio.h>
void main()
{
char in[20],i,out;
for(i=0;i<20;i++)
scanf("%s",&in[i]);
for(i=20;i=0;i--)
{
if(in[i]!='\0')
out=in[i];
printf("%s",out);
else 
break;
}
}
