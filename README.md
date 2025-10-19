# ilk-proje
başlangıç
#include <stdio.h>
int main (){
int R1,R2,R3;
	float R12;
	float Res;
	printf("R1 giriniz:");
	scanf("%d",&R1);
	printf("R2 giriniz:");
	scanf("%d",&R2);
	printf("R3 giriniz:");
	scanf("%d",&R3);
	R12=(1.0/((1.0/R1)+(1.0/R2)));
	printf("R12=%.3f",R12);
	Res =(R12+R3);
	printf("\nRes=%.3f",Res);
	
	return 0
	}

