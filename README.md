# Facu
#include<stdio.h>
#include<stdlib.h>
main(){
       int a, b, c, mult;
       //soliciação ao usuario
       printf("Digite um numero para exibir a tabuada\n");
       //armazenamento do valor inserido
       scanf("%d", &a);
       //pular uma linha para melhor visualisação
       printf("\n");
       //sistema de repetição para montar a tabuada
       for(b=1; b<=10; b++){
                       //para fazer a multiplicação
                         mult= a*b;
                         //exibir a tabuada
                         printf("%d X %d = %d\n", a, b, mult);
                     
                }
system("pause>>null");
}
