//# number-to-day.c//
#include<stdio.h>
int main()
{
    int num;
    printf("Enter number:");
    scanf("%d",&num);
    switch(num)
    {
        case 1:
        printf("It's sunday");
        break;
        case 2:
        printf("It's monday");
        break;
        case 3:
        printf("It's tuesday");
        break;
        case 4:
        printf("It's wednesday");
        break;
        case 5:
        printf("It's thursday");
        break;
        case 6:
        printf("It's friday");
        break;
        case 7:
        printf("It's saturday");
        break;
        default:
        printf("invalid input");
    }
    return 0;
}
