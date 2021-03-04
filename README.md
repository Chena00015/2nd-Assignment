# 2nd-Assignment
#include <stdio.h>

int main()
{   
    float grade1, grade2, grade3, grade4, grade5, sum, average;
    
   
    
    printf("Enter grade obtained in subject 1 :");
    scanf("%f", &grade1);
    printf("Enter grade obtained in subject 2 :");
    scanf("%f", &grade2);
    printf("Enter grade obtained in subject 3 :");
    scanf("%f", &grade3);
    printf("Enter grade obtained in subject 4 :");
    scanf("%f", &grade4);
    printf("Enter grade obtained in subject 5 :");
    scanf("%f", &grade5);

    average = (grade1 + grade2 + grade3 + grade4 + grade5) /5;
    printf("Average : %0.2f\n", average);
   

    return 0;
}
