#include <stdio.h>

// A Torre

void torre(int passos) {
    if (passos == 0) return; // caso base

    printf("Direita\n"); // movimento
    torre(passos - 1); // chamada recursiva
}

// Bispo (loops aninhados)

void bispo(int passos) {
    if (passos == 0) return; // base

    // externo = vertical / loop interno = horizontal
    for (int i = 0; i < 1; i++) { // vertical
        for (int j = 0; j < 1; j++) { // horizontal
            printf("Diagonal Cima Direita\n");
        }
    }

    bispo(passos - 1); 
}

// A Temida RAINHAA MUAHAHAHAHA!

void rainha(int passos) {
    if (passos == 0) return; // a base ataca novamente

    printf("Esquerda\n");
    rainha(passos - 1);
}

// O Cavalo

void cavalo() {
    printf("Movimento do Cavalo:\n");

    int cima = 0;
    int direita = 0;

    // esse aqui simula os movimentos compostos
    for (int i = 0; i < 3; i++) {
        if (cima < 2) {
            printf("Cima\n");
            cima++;
            continue; // volta ao início do loop até subir 2 vezes
        }

        for (int j = 0; j < 3; j++) {
            if (direita < 1) {
                printf("Direita\n");
                direita++;
                break; // sai do loop interno
            }
        }
        break; // fechar bonitinho o movimento em "L"
    }
}

// O tal do funcional tá aqui

int main() {
    int casasTorre = 3;
    int casasBispo = 2;
    int casasRainha = 3;

    printf("=== MOVIMENTO DA TORRE ===\n");
    torre(casasTorre);

    printf("\n=== MOVIMENTO DO BISPO ===\n");
    bispo(casasBispo);

    printf("\n=== MOVIMENTO DA RAINHA ===\n");
    rainha(casasRainha);

    printf("\n=== MOVIMENTO DO CAVALO ===\n");
    cavalo();

    return 0;
}
