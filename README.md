# Exercicio10

#include <stdio.h>
#include <stdlib.h>

int main()

{
    system("color 0b");
    int i=1;
    float fahr, cel, inferior, superior;

    printf("Digite o limite inferior ");
    scanf("%f", &inferior);

    printf("Digite o limite superior ");
    scanf("%f", &superior);

    fahr=inferior;
    while (fahr<=superior)
    {
        cel = 5 * (fahr-32)/9;
        printf("%.0f Fahrenheit e igual a %.2f Celsius\n",fahr,cel);
        fahr=fahr+i;
    }
 return 0;
}
