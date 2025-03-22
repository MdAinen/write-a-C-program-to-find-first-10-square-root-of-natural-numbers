#include <stdio.h>
#include <math.h>

int main() {
    int i;
    printf("The first 10 square roots of natural numbers are:\n");
    for (i = 1; i <= 10; i++) {
        printf("Square root of %d: %.2f\n", i, sqrt(i));
    }
    return 0;
}
