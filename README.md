# Simple-Calculator
Hy Everyone   This Code is my Frist project. 

#include <stdio.h>

int main()
{
    char op;
    double a, b, result;
    int i = 1;
    while (1)
    {
        printf("Enter Operator (+ - * / )");
        scanf("%c", &op);
        switch (op)
        {
        case '+':
            printf("Addition:\n");
            printf("Enter the Value of A ,B:-");
            scanf("%lf%lf", &a, &b);
            result = a + b;
            printf("%lf + %lf = %lf\n", a, b, result);
            break;
        case '-':
            printf("Subtration:\n");
            printf("Enter the Value of A :-\n B:-\n");
            scanf("%lf%lf", &a, &b);
            result = a - b;
            printf("%lf - %lf = %lf\n", a, b, result);
            break;
        case '*':
            printf("|Multiplication\n");
            printf("Enter the Value of A :-\n B:-\n");
            scanf("%lf%lf", &a, &b);
            result = a * b;
            printf("%lf * %lf = %lf\n", a, b, result);
            break;
        case '/':
            printf("Divide:\n");
            printf("Enter the Value of A :-\n B:-\n");
            scanf("%lf%lf", &a, &b);
            result = a / b;
            printf("%lf / %lf = %lf\n", a, b, result);
            break;
            i++;
        }
    }
    return 0;
}
