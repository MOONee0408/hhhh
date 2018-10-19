#include<stdio.h>
#include<stdlib.h>
#include<math.h>
int main()
{
system("color f0");
const double PI=3.141592;
int r;
float inicial, final, inc, s, c;
printf("\nProgramado por Jessica Elizabeth Ortiz Camacho\n\nEste programa obtiene el valor de la función seno desde el valor inicial hasta el final con el incremento que el usuario ingrese");
r=1;
while (r==1)
        {
        printf("\n¿Desde qué valor desea iniciar?\n");
        scanf("%f", &inicial);
        printf("\n¿En qué valor desea terminar?\n");
        scanf("%f", &final);
        printf("\n¿Con qué incremento?\n");
        scanf("%f", &inc);
        while (inc<0)
                {
                printf("\nPor favor ingrese un número válido\n");
                scanf("%f",&inc);
                }
