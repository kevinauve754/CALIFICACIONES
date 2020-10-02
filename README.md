# CALIFICACIONES
#include <stdio.h> <stdlib.h>

int main()
{
    char a1, a2, a3;

    float prom;
    char A='10';
    char B='9';
    char C='8';
    char D='7';
    char E='6';
    char F='5';

    printf("Introduzca sus 3 calificaciones con letras \n");



    printf("PRIMER CALIFICACION: \n");
     scanf("%c", &a1);
    printf("SEGUNDA CALIFICACION: \n");
     scanf("%c", &a2);
    printf("TERCERA CALIFICACION: \n");
     scanf("%c", &a3);

    prom=(a1+a2+a3)/3;

    if(prom>9.5)
    {
        printf("TIENE A");
    }
    else if(prom>8.5 && prom<=9.4)
    {
        printf("TIENE B");
    }
    else if(prom>7.5 && prom<=8.4)
    {
        printf("TIENE C");
    }
    else if(prom>6.5 && prom<=7.4)
    {
        printf("TIENE D");
    }
    else if(prom>5.5 && prom<=6.4)
    {
        printf("TIENE E");
    }
    else if(prom>4.5 && prom<=5.4)
    {
        printf("TIENE F");
    }

}
