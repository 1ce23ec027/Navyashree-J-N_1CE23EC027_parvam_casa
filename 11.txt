#include<stdio.h>
#include<stdlib.h>
void main()
{
    int row,cols;
    printf("\n enter no. of rows and cols:");
    scanf("%d%d",&row,&cols);
    int Arr1[row][cols];
    printf("\n enter the array values:");
    for(int i=0;i<row;i++)
        scanf("%d",&Arr1[i]);
        printf("\n values in the array are:\n");
        for(int j=0;j<cols;j++)
            printf("%d",Arr1[j]);
            printf("\n");
}
{
    int sum=0;
    for(int i=0;i<row;i++)
    {
         for(int j=0;j<cols;j++)
         {
            sum=sum+Arr1[i][j];
         }
    }
    printf("SUM of Array1 is:",sum);
}