#include <stdio.h>
int main()
{
	int t1= 0, t2=1, ts, num, cont; //t1: termo antecessor de t2; t2; termo antecessor de ts; ts: termo sequencial atual//
	printf("Sequencia de Fibonacci\n");
	printf("\nDigite um numero:\n");
	
	scanf("%d", &num);
	
	printf("\n\n A sequencia eh:\n\n");
	
	
	printf("%d \n%d\n", t1, t2);
	cont = 2;
	while (cont<num)
	{
		ts = t1+t2;
		t1 = t2;
		t2 = ts;
		
		printf("%d\n", ts);
		cont++;
