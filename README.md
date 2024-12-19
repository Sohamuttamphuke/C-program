#include <stdio.h>

int main() {
    int num1, num2, temp;

    // Input two numbers
    printf("Enter first number: ");
    scanf("%d", &num1);
    printf("Enter second number: ");
    scanf("%d", &num2);

    // Display original values
    printf("\nBefore swapping:\n");
    printf("num1 = %d, num2 = %d\n", num1, num2);

    // Swapping logic
    temp = num1;
    num1 = num2;
    num2 = temp;

    // Display swapped values
    printf("\nAfter swapping:\n");
    printf("num1 = %d, num2 = %
