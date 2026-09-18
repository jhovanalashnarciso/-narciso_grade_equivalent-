# -narciso_grade_equivalent-


#include <stdio.h>

int main() {
    int score;
    char Grade;

    printf("Enter your grade:");
    scanf("%d", &score);

    if (score >= 90)
        printf("Grade = 'A'");
    else if (score >= 80)
        printf("Grade = 'B'");
    else if (score >= 70)
        printf("Grade = 'C'");
    else if (score >= 60)
        printf("Grade = 'D'");
    else
        printf("Grade = 'F'");

    printf("%c\n", Grade);

    return 0;
}