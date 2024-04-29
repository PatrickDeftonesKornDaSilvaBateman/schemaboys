#include <stdio.h>
#include <stdlib.h>

float soma(float a, float b) {
    return a + b;
}

float subtracao(float a, float b) {
    return a - b;
}

float multiplicacao(float a, float b) {
    return a * b;
}

float divisao(float a, float b) {
    if (b == 0) {
        printf("Erro: Divisao por zero!\n");
        return 0;
    } else {
        return a / b;
    }
}

int main() {
    char continuar;
    
    do {
        float numero1, numero2;
        char operador;
	
        printf("Digite o primeiro numero: ");
        scanf("%f", &numero1);
        printf("Digite o segundo numero: ");
        scanf("%f", &numero2);
        printf("Escolha a operacao (+, -, *, /): ");
        scanf(" %c", &operador);
   
        switch (operador) {
            case '+':
                printf("Resultado: %.2f\n", soma(numero1, numero2));
                break;
            case '-':
                printf("Resultado: %.2f\n", subtracao(numero1, numero2));
                break;
            case '*':
                printf("Resultado: %.2f\n", multiplicacao(numero1, numero2));
                break;
            case '/':
                printf("Resultado: %.2f\n", divisao(numero1, numero2));
                break;
            default:
                printf("Operador invalido!\n");
        }

        printf("Deseja continuar? (s/n): ");
        scanf(" %c", &continuar);
        
    } while (continuar == 's' || continuar == 'S');
    
    printf("Encerrando a calculadora.\n");

    return 0;
}

