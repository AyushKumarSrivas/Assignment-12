# Assignment-12
1. #include <stdio.h>

void printNaturalNumbers(int n) {
    if (n == 0)
        return;
    printNaturalNumbers(n - 1);
    printf("%d ", n);
}

int main() {
    int n = 10;
    printf("First %d natural numbers are: ", n);
    printNaturalNumbers(n);
    printf("\n");
    return 0;
}

2. #include <stdio.h>

void printNaturalNumbersReverse(int n) {
    if (n == 0)
        return;
    printf("%d ", n);
    printNaturalNumbersReverse(n - 1);
}

int main() {
    int n = 10;
    printf("First %d natural numbers in reverse order are: ", n);
    printNaturalNumbersReverse(n);
    printf("\n");
    return 0;
}

3. #include <stdio.h>

void printOddNumbers(int n, int current) {
    if (n == 0)
        return;
    printf("%d ", current);
    printOddNumbers(n - 1, current + 2);
}

int main() {
    int n = 10;
    printf("First %d odd natural numbers are: ", n);
    printOddNumbers(n, 1);
    printf("\n");
    return 0;
}

4. #include <stdio.h>

void printOddNumbersReverse(int n, int current) {
    if (n == 0)
        return;
    printOddNumbersReverse(n - 1, current + 2);
    printf("%d ", current);
}

int main() {
    int n = 10;
    printf("First %d odd natural numbers in reverse order are: ", n);
    printOddNumbersReverse(n, 1);
    printf("\n");
    return 0;
}

5. #include <stdio.h>

void printEvenNumbers(int n, int current) {
    if (n == 0)
        return;
    printf("%d ", current);
    printEvenNumbers(n - 1, current + 2);
}

int main() {
    int n = 10;
    printf("First %d even natural numbers are: ", n);
    printEvenNumbers(n, 2);
    printf("\n");
    return 0;
}

6. #include <stdio.h>

void printEvenNumbersReverse(int n, int current) {
    if (n == 0)
        return;
    printEvenNumbersReverse(n - 1, current + 2);
    printf("%d ", current);
}

int main() {
    int n = 10;
    printf("First %d even natural numbers in reverse order are: ", n);
    printEvenNumbersReverse(n, 2);
    printf("\n");
    return 0;
}

7. #include <stdio.h>

void printSquares(int n) {
    if (n == 0)
        return;
    printSquares(n - 1);
    printf("%d ", n * n);
}

int main() {
    int n = 10;
    printf("Squares of first %d natural numbers are: ", n);
    printSquares(n);
    printf("\n");
    return 0;
}

8. #include <stdio.h>

void printBinary(int n) {
    if (n == 0)
        return;
    printBinary(n / 2);
    printf("%d", n % 2);
}

int main() {
    int n = 13;
    printf("Binary of %d is: ", n);
    printBinary(n);
    printf("\n");
    return 0;
}

9. #include <stdio.h>

void printOctal(int n) {
    if (n == 0)
        return;
    printOctal(n / 8);
    printf("%d", n % 8);
}

int main() {
    int n = 65;
    printf("Octal of %d is: ", n);
    printOctal(n);
    printf("\n");
    return 0;
}

10. #include <stdio.h>

void printReverse(int n) {
    if (n == 0)
        return;
    printf("%d", n % 10);
    printReverse(n / 10);
}

int main() {
    int n = 12345;
    printf("Reverse of %d is: ", n);
    printReverse(n);
    printf("\n");
    return 0;
}
