# -Factorial-of-a-Number-Using-Recursion
C programming
#include<stdio.h>
int main()
{
    int n,factorial(n);
    scanf("%d",&n);
    printf("%d",factorial(n));
}

int factorial(n){
    if (n>=1)
        return n*factorial(n-1);
    else
        return 1;
    }
