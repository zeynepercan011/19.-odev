# 19.-odev

// asal say� m� de�il mi?

#include<stdio.h>

int asal(int x);

int main()
{
	int x;
	
	printf("asal olup olmadigini ogrenmek istediginiz sayiyi giriniz: \n");
	scanf("%d" , &x);
	
if(asal(x)==0)
{
	printf("asal degildir.");
}

else
printf("asal sayidir.");
	
	return 0;
	
}

int asal(int sayi)
{
	int i;
	
	for(i=2;i<sayi;i++)
	{
		if(sayi%i==0)
		{
			return 0;
		}
		
	
}
return 1;
}
