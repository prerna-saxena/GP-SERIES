# GP-SERIES



GP SERIES PRINT

#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#include <math.h>

int three(int n)
{
    int x;
    x=pow(3, n-1);
    printf("%d\n", x);
    
}
int two(int n)
{
    int x;
    x=pow(2, n-1);
    printf("%d\n", x);
    
}
int main()
{
int n;
scanf("%d", &n);
if(n%2==0)
{
    three(n/2);
}
else
{
    two(n/2+1);
}
return 0;
}
