# exercicios-em-c-resolvidos

### Fazer um programa para receber 3 valores inteiros do usuário e mostrar a sua média (que pode não ser inteira).

```
//
// Created by luizg on 02/09/2022.
//

/*
 * 2) Fazer um programa para receber 3 valores inteiros do usuário e mostrar a sua média (que pode não ser inteira).
 */

#include <stdio.h>
void mediaTresValores()
{
    float media = 0.000, nota1 = 0.0000, nota2 = 0.0000, nota3 = 0.0000;

    printf("Digite a primeira nota: ");
    scanf("%f", &nota1);

    printf("Digite a Segunda nota: ");
    scanf("%f", &nota2);

    printf("Digite a Segunda nota: ");
    scanf("%f", &nota3);

    media = (nota1 + nota2 + nota3) / 3;

    printf("A media final foi %.2f", media);
}

```
