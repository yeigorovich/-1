#include <stdio.h>

int main() {
    int t1, t2, t3;
    double total_time;

    // Ввід трьох значень t1, t2, t3
    scanf("%d %d %d", &t1, &t2, &t3);

    // Знаходження загального часу
    total_time = 1.0 / (1.0 / t1 + 1.0 / t2 + 1.0 / t3);

    // Вивід результату з округленням до 2 знаків після коми
    printf("%.2f\n", total_time);

    return 0;
}
