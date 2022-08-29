# codesteste
testing basic code
#include <stdio.h>

int main()
{
    float num1, num2;
    
    printf("\n\t*********teste************\n");
    printf("\n\tdigite o 1º  e o 2º numero de 1 a 10:     "  );
    //printf("\n\tdigite o 2º numero de 1 a 10:  "  );
    scanf("%f%f", &num1, &num2);
    if (num1,num2 > 0 && num1,num2 < 11){
        printf("\n\tO 1º numero é igual a :%.2f e o 2º numero é igual a: %.2f" , num1, num2);
        printf("\n\tA soma do 1º e 2º numero é: %.2f", num1 + num2);
        printf("\n\tA subtração do 1º e 2º numero é: %.2f", num1 - num2);
        printf("\n\tA multiplicação do 1º e 2º numero é: %.2f", num1 * num2);
        printf("\n\tA divisão do 1º e 2º numero é: %.2f", num1 / num2);
    }
    else{
        printf("n\tEntrada invalida");
    }
    

    return 0;
}
