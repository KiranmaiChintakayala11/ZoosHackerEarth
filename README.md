#include<stdio.h>
int main()
{
	int a=0,b=0,i;
	char str[20];
	scanf("%s",str);
	for(i=0;str[i]!='\0';i++)
	{
		if(str[i]=='z')
		a++;
		if(str[i]=='o')
		b++;
	}
	if((2*a)==b)
	printf("Yes");
	else
	printf("No");

}
