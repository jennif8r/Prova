#include <stdio.h>
//Questão Tres: 
int main() {
    // Sequência a)
    int a[5] = {1, 3, 5, 7, 0}; // Array com os primeiros 5 números da sequência
    int next_a = a[3] + 2; // Próximo elemento da sequência
    printf("a) Próximo elemento: %d\n", next_a);

    // Sequência b)
    int b[6] = {2, 4, 8, 16, 32, 64}; // Array com os primeiros 6 números da sequência
    int next_b = b[5] * 2; // Próximo elemento da sequência
    printf("b) Próximo elemento: %d\n", next_b);

    // Sequência c)
    int c[7] = {0, 1, 4, 9, 16, 25, 36}; // Array com os primeiros 7 números da sequência
    int next_c = c[6] + 13; // Próximo elemento da sequência
    printf("c) Próximo elemento: %d\n", next_c);

    // Sequência d)
    int d[5] = {4, 16, 36, 64, 0}; // Array com os primeiros 5 números da sequência
    int next_d = d[3] + 36; // Próximo elemento da sequência
    printf("d) Próximo elemento: %d\n", next_d);

    // Sequência e)
    int e[7] = {1, 1, 2, 3, 5, 8, 0}; // Array com os primeiros 7 números da sequência
    int next_e = e[5] + e[6]; // Próximo elemento da sequência
    printf("e) Próximo elemento: %d\n", next_e);

    // Sequência f)
    int f[7] = {2, 10, 12, 16, 17, 18, 19}; // Array com os primeiros 7 números da sequência
    int next_f = f[6] + 1; // Próximo elemento da sequência
    printf("f) Próximo elemento: %d\n", next_f);

    return 0;
}
