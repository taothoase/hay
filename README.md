# hay
#include <stdio.h>
#include <conio.h>

void main()#include <stdio.h>
#include <conio.h>

void main()
{
	int n, i, j, s, ts;
	clrscr();
	printf("Nhap n=");
	scanf("%d", &n);
	printf("Cac so hoan hao khong vuot qua %d la :", n);

	for (ts = 0, i = 2; i <= n; i++)
	{
		s = 1;
		for (j = 2; j <= i / 2; j++)
			if (i % j == 0) s += j;
		if (s == i)
		{
			ts++;
			printf("\n %d = 1", i);#include <stdio.h>
#include <conio.h>

void main()
{
	int n, i, j, s, ts;
	clrscr();
	printf("Nhap n=");
	scanf("%d", &n);
	printf("Cac so hoan hao khong vuot qua %d la :", n);

	for (ts = 0, i = 2; i <= n; i++)
	{
		s = 1;
		for (j = 2; j <= i / 2; j++)
			if (i % j == 0) s += j;
		if (s == i)
		{
			ts++;
			printf("\n %d = 1", i);
			for (j = 2; j <= i / 2; j++)
				if (i % j == 0) printf(" + %d", j);
		}
	}

	if (ts) printf("\nCo tat ca %d so hoan hao", ts);
	else printf("\nKhong co so hoan hao nao");
	getch();
}
			for (j = 2; j <= i / 2; j++)
				if (i % j == 0) printf(" + %d", j);
		}
	}

	if (ts) printf("\nCo tat ca %d so hoan hao", ts);
	else printf("\nKhong co so hoan hao nao");
	getch();
}
{
	int n, i, j, s, ts;
	clrscr();
	printf("Nhap n=");
	scanf("%d", &n);
	printf("Cac so hoan hao khong vuot qua %d la :", n);

	for (ts = 0, i = 2; i <= n; i++)
	{
		s = 1;
		for (j = 2; j <= i / 2; j++)
			if (i % j == 0) s += j;
		if (s == i)
		{
			ts++;
			printf("\n %d = 1", i);
			for (j = 2; j <= i / 2; j++)
				if (i % j == 0) printf(" + %d", j);
		}
	}

	if (ts) printf("\nCo tat ca %d so hoan hao", ts);
	else printf("\nKhong co so hoan hao nao");
	getch();
}
