# C-LANGUAGE-ARRAY
ARRAY CODE
#include<stdio.h>
#include<conio.h>
void main ()
{
int i,n,y,j,a[5];
printf ("enter the array");
scanf ("%d",&n);
for(i=0;i<n;i++)
{
	scanf("%d",&a[i]);
	
}
for(i=0;i<n;i++)
{
for (j=j+1;j<n;j++)
{
	if(a[j]<a[i])
	y=a[i];
	a[i]=a[j];
	a[j]=y;
}
}

printf("the acending order\n");
for(i=0;i<n;i++)
{
	printf("%d",&a[i]);
}
getch();
}
