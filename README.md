# Atividade-15

#include<stdio.h>
#include <math.h>


int main (){
	
	int numero;
	int expoente;

		
		printf("diga um numero");
			scanf("%i",&numero);
		
		printf("diga um numero para o expoente");
			scanf("%i",&expoente);
		
		
	int potencia = pow (numero, expoente);
	
	printf("\na potencia desse numero e %i",potencia);	


	
}
