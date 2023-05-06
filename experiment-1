#include<stdio.h>
int main()
{
	int r1,r2,c1,c2;
	printf("enter the row1:");
	scanf("%d",&r1);
	printf("enter the colomn1:");
	scanf("%d",&c1);
	printf("enter the row2:");
	scanf("%d",&r2);
	printf("enter the colomn2:");
	scanf("%d",&c2);
	if(c1!=r2)
	{
		printf("matrix multiplication is not possible");
	}
	else{
	int a[10][10],b[10][10],c[10][10],i,j,k;
	
	printf("enter the matrix of A:\n");
	for(i=0;i<r1;i++)
	{
		for(j=0;j<c1;j++)
		{
			scanf("%d",&a[i][j]);
		}
	}
	printf("enter the matrix of B:\n");
	for(i=0;i<r2;i++)
	{
		for(j=0;j<c2;j++)
		{
			scanf("%d",&b[i][j]);
		}
	}
	for(i=0;i<r1;i++)
	{
		for(j=0;j<c2;j++)
		{
			c[i][j]=0;
			for(k=0;k<r2;k++)
		    {
		    	c[i][j]=c[i][j]+a[i][k]*b[k][j];
			}
		}
	}
	printf("matrix multiplication:\n");
	for(i=0;i<r1;i++)
	{
		for(j=0;j<c2;j++)
		{
				printf("%d\t",c[i][j]);
		}
		printf("\n");
	}
}
return 0;
}
