#include <stdio.h>
int main()
{
    int marks;
    printf("enter your arks betwwen 0 to 100\n");
    scanf("%d",&marks);
    switch(marks/10)
    {
        case 10:
        case 9:
        printf("your grade : A\n");
        break;
        case 8:
        case 7:
        printf("your grade : B\n");
        break;
        case 6:
        case 5:
        printf("your grade: C\n");
        break;
        case 4:
        printf("your grade: D\n");
        break;
        default:
        printf("failed");
        
    }
}
