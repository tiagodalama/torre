#include <stdio.h>

int main() {
    // Número de casas que cada peça vai se mover
    int casas_torre = 5;
    int casas_bispo = 5;
    int casas_rainha = 8;

    // --- Movimento da Torre ---
    // Torre se move 5 casas para a direita usando "for"
    printf("Movimento da Torre (5 casas para a direita):\n");
    for (int i = 0; i < casas_torre; i++) {
        printf("Direita\n");
    }

    printf("\n");

    // --- Movimento do Bispo ---
    // Bispo se move 5 casas na diagonal para cima e direita usando "while"
    printf("Movimento do Bispo (5 casas diagonal para cima e direita):\n");
    int passo_bispo = 0;
    while (passo_bispo < casas_bispo) {
        printf("Cima, Direita\n");
        passo_bispo++;
    }

    printf("\n");

    // --- Movimento da Rainha ---
    // Rainha se move 8 casas para a esquerda usando "do-while"
    printf("Movimento da Rainha (8 casas para a esquerda):\n");
    int passo_rainha = 0;
    do {
        printf("Esquerda\n");
        passo_rainha++;
    } while (passo_rainha < casas_rainha);

    return 0;
}
