#include <stdio.h>

int main() {
    int marks;
    printf("Enter your marks (0 - 100): ");
    scanf("%d", &marks);
    if (marks < 0 || marks > 100) {
        printf("Invalid Marks! Please enter between 0 and 100.\n");
    } else {
        // Grade Calculation
        if (marks >= 90) {
            printf("Grade: A\n");
        } else if (marks >= 75) {
            printf("Grade: B\n");
        } else if (marks >= 60) {
            printf("Grade: C\n");
        } else if (marks >= 40) {
            printf("Grade: D\n");
        } else {
            printf("Grade: F (Fail)\n");
        }
    }
    return 0;
}
