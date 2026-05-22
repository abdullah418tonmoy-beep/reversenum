#include<stdio.h>
int main()

{
    int a,reminder , reverse= 0;
    printf(" ENTER YOUR NUMBER: ");
    scanf("%d",&a);

    while(a !=0)
    {
        reminder = a % 10;
         reverse= reverse* 10 + reminder;
         a/=10;

    }

printf(" reverse NUMBER: %d",reverse);

return 0;
}


