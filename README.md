//do-while
#include <stdio.h>

int main() 
{
    int n;
    int sum;
    scanf("%d",&n);
    while(n>9)
    {
        int sum=0;
    while(n>0)
        {
            int rem=n%10;
            sum=sum+rem;
            n=n/10;
        }
            n=sum;
     }
    printf("%d",n);
}
