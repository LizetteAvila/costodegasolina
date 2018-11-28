# costodegasolina
Como saber el costo de la gasolina.
#include<math.h>
#include<stdio.h>
#include<conio.h>

int main()
{float base, altura, area, ancho, capacidad, magna,premium, diesel, tanque;
 printf("base:   "); scanf("%f", &base  );
 printf("altura: "); scanf("%f", &altura);
 printf("ancho:  "); scanf("%f", &ancho );
 area = (base) * (altura);
 printf("\n El area del rectangulo es: %f cm", area);     
 tanque= (area) * (ancho);
 printf("\n La medida del tanque es de: %fcm3", tanque); capacidad= (tanque) / 1000;
 printf ("\n La capacidad del es tanque es de: %f L", capacidad);
 
 magna= (capacidad) * 10;  printf("\n El precio de la gasolina magna es de: %f $", magna);
 premium= (capacidad) *12;printf("\n El precio de la gasolina premium es de: %f $", premium);
 diesel= (capacidad) * 15; printf("\n El precio del diesel es de: %f $", diesel);
 
 
 getch();
 return 0;
 
 
 
}
