#include <stdio.h>
#include <stdlib.h>
#include <conio.h>
void imprimir_menu();
void leer_opcion(int &opt);
float leer_variable();
float suma (float x, float y);
float resta(float x, float y);
float multiplicacion(float x, float y);
float division(float x, float y);
void leer_repet(char&repet);
int main(){
    float a,b,c;
    int opt;
    char repet;
    do{
    imprimir_menu();
    leer_opcion(opt);
a=leer_variable();
b=leer_variable();
    switch(opt){
         case 1:
           c=suma(a,b);
               break;
         case 2:
           c=resta(a,b);
               break;
         case 3:
           c=multiplicacion(a,b);
               break;
         case 4:
           c=division(a,b);
           break;
         default:
             leer_opcion(opt);
    }
    printf("El resuultado es:%f\n",c);
        leer_repet(repet);
    } while(repet=='s'||repet=='S');
    }

void imprimir_menu(){
printf ("1.-Suma\n");
printf ("2.-Resta\n");
printf ("3.-Multiplicacion\n");
printf ("4.-Division\n");
}
float leer_variable(){
float variable;
printf("introduce un valor:\n");
scanf("%f",&variable);
return variable;
}
void leer_opcion(int &opt){
printf("introduce una opcion:\n");
scanf("%d",&opt);
}
float suma(float x, float y){
return x+y;
}
float resta(float x, float y){
return x-y;
}
float multiplicacion(float x, float y){
return x*y;
}
float division(float x, float y){
    while(y==0){
        y=leer_variable();
    }
    return(x/y);
}
 void leer_repet(char&repet){
printf("¿Desea realizar otra operacion?:s \n");
repet=getch();
}
