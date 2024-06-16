 #include<stdio.h>
int main()
{
    int n;
    printf("enter n value");
    scanf("%d",&n);
    for(int i=1;i<=n;i++)//row
    
    

    {
        for(int k=1;k<=n-i;k++)
        {
            printf(" ");
        }
        for(int j=1;j<=i;j++)
        {
        printf("%d",j);
    }
    printf("\n");
    }
}
