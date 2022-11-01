# treine
Algoritmo dobro e triplo

#include <stdio.h>
#include <math.h>
float n1,n2,soma;

int main(){
    printf("Digite um numero: ");
    scanf("%f",&n1);
    printf("\nDigite o segundo numero: ");
    scanf("%f",&n2);
    soma=n1+n2;
    printf("\nA soma dos numeros e %.2f\n",soma);
    
  if(soma>=10){
   printf("\nO valor desta soma mudou para o dobro = %.2f",soma*2);
    }
  else if (soma<10){
    printf("\nO valor desta soma mudou para o triplo = %.2f",soma*3);
     }
    
    
    
    

    
  return 0;
}
