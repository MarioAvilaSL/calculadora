#include <iostream>
#include <math.h>
#include <stdlib.h>
#include <windows.h>

using namespace std;
int main()
{
cout<<"#######################################################################################################################\n";
cout<<"#                                                  Calculadora v 2.1.0                                                #\n";
cout<<"#######################################################################################################################\n";
     double X;  //para aceptar dos numeros en una variante
   {
     cout << "\n#                                               Desarrollado por Mario A.                                             #\n#                                                -Calculadora Avanzada-                                               #\n#######################################################################################################################\n\nElige la opcion que desea realizar:\n\n------------------------------------------\n Funciones Matematicas\n1. Sumar\n2. Restar\n3. Multiplicar\n4. Dividir\n5. Raiz cuadrada\n6. Porcentaje\n7. Numero elevado a otro numero\n\n------------------------------------------\n Funciones Trigonometricas\n8. Coseno del angulo\n9. Seno del angulo\n10. Tangente\n11. Arco tangente\n\n------------------------------------------\n Funciones Logaritmicas\n12. Logaritmo natural\n13. Logaritmo decimal\n\n------------------------------------------\n Numeros aleatorios\n14. Numero aleatorio\n15. Dos numeros aleatorios\n16. Cinco numeros aleatorios\n17. 10 numeros aleatorios\n18. 20 numeros aleatorios\n19. 100 numeros aleatorios\n20. 1000 numeros aleatorios\n21. 1000000 numeros aleatorios\n\n------------------------------------------\n Conversion de unidades\n22. Gramos a libras\n23. Libras a gramos\n24. Gramos a kilogramos\n25. kilogramos a gramos\n26. Libras a kilogramos\n27. kilogramos a Libras\n28. Gramos a toneladas\n29. Toneladas a gramos\n30. Libras a toneladas\n31. Toneladas a libras\n32. Kilogramos a toneladas\n33. Toneladas a kilogramos\n\n------------------------------------------\n Cronometro\n34. Cronometro con historial\n35. Cronometro normal\n\n------------------------------------------\n Conversion de tiempo\n36. Segundos a minutos\n37. Segundos a horas\n38. Segundos a dias\n39. Minutos a segundos\n40. Minutos a horas\n41. Minutos a dias\n\n------------------------------------------\n";
     cin >> X;
                     if(X == 1)
{ //Sumar
double sum1, sum2;
cout << "\nEscribe el primer digito: ";
cin >> sum1;
cout << "Escribe el segundo digito: ";
cin >> sum2;
cout << "El resultado de la suma es " << sum1 + sum2 << "\n" << endl;
  system("pause>nul");
    }

                    if(X == 2)
{ //Restar
double res1, res2;
cout << "\nEscribe el primer digito: ";
cin >> res1;
cout << "Escribe el segundo digito: ";
cin >> res2;
cout << "El resultado de la resta es " << res1 - res2 << endl;
    system("pause>nul");
      }

                   if(X == 3)
 { //Multiplicar dos cifras
double mul1, mul2;
cout << "\nEscribe el primer digito: ";
cin >> mul1;
cout << "Escribe el segundo digito: ";
cin >> mul2;
cout << "El resultado de la multiplicacion es " << mul1 * mul2 << endl;
     system("pause>nul");

    }
       if(X == 4)
{ //Dividir
double div1, div2;
cout << "\nEscribe el primer digito: ";
cin >> div1;
cout << "Escribe el segundo digito: ";
cin >> div2;
cout << "El resultado de la división es " << div1 / div2 << endl;
    system("pause>nul");

    }
              if(X == 5)
{    //Raiz cuadrada
double raiz;
cout << "\nEscribe el digito: ";
cin >> raiz;
cout << "La raiz cuadrada es " << sqrt(raiz) << endl;
system("pause>nul");
   }

      if(X == 6)
{ //Porcentaje
double por1, por2;
cout << "\nEscribe el digito: ";
cin >> por1;
cout << "Escribe el porcentaje: ";
cin >> por2;
cout << "El porcentaje es " << (por1 * por2)/100 << endl;
   system("pause>nul");
    }

      if(X == 7)
{ //Elevar un número a otro exponente
double num1, num2;
cout << "\nEscribe el digito:";
cin >> num1;
cout << "Escribe digito elevado: ";
cin >> num2;
cout << "El resultado es " << pow(num1, num2) << endl;
     system("pause>nul");
   }

     if(X == 8)
  { //Coseno
double c;
cout << "\nEscribe el digito: ";
cin >> c;
cout << "El coseno del angulo es " << cos(c) << endl;
system("pause>nul");
}

    if(X == 9)
{ //Seno
double s;
cout << "\nEscribe el digito: ";
cin >> s;
cout << "El seno del angulo es " << sin(s) << endl;
   system("pause>nul");
    }

   if(X == 10)
{ //Tangente
double t;
cout << "\nEscribe un digito: ";
cin >> t;
cout << "La tangente del angulo es " << tan(t) << endl;
   system("pause>nul");
 }

    if(X == 12)
 { //Logaritmo natural
double l;
cout << "\nEscribe un digito: ";
cin >> l;
cout << "El logaritmo natural del argumento es " << log(l) << endl;
   system("pause>nul");
    }

    if(X == 13)
    { //Logaritmo decimal
double l1;
cout << "\nEscribe un digito: ";
cin >> l1;
cout << "El logaritmo decimal del argumento es " << log10(l1) << endl;
  system("pause>nul");
    }

    if (X == 14)
    {
int main();
int i;
cout << "Numero aleatorio:\n\n";
for(i=1; i<=1; i++)
cout << rand() << endl;
  system("pause>nu1");
       }

       if (X == 15)
       {
int main();
int i;
cout << "Dos numeros aleatorios:\n\n";
for(i=1; i<=2; i++)
cout << rand() << endl;
     system("pause>nu1");
          }

        if (X == 16)
          {
int main();
int i;
cout << "Cinco numeros aleatorios:\n\n";
for(i=1; i<=5; i++)
cout << rand() << endl;
    system("pause>nu1");
             }

             if (X == 17)
               {
int main();
int i;
cout << "10 numeros aleatorios:\n\n";
for(i=1; i<=10; i++)
cout << rand() << endl;
 system("pause>nu1");
          }

          if (X == 18)
            {
int main();
int i;
cout << "20 numeros aleatorios:\n\n";
for(i=1; i<=20; i++)
cout << rand() << endl;
system("pause>nu1");
       }

       if (X == 19)
         {
int main();
int i;
cout << "100 numeros aleatorios:\n\n";
for(i=1; i<=100; i++)
cout << rand() << endl;
system("pause>nu1");
    }

    if (X == 20)
      {
int main();
int i;
cout << "1000 numeros aleatorios:\n\n";
for(i=1; i<=1000; i++)
cout << rand() << endl;
  system("pause>nu1");
     }

     if (X == 21)
       {
int main();
int i;
cout << "1000000 numeros aleatorios:\n\n";
for(i=1; i<=1000000; i++)
cout << rand() << endl;
     system("pause>nu1");
      }

      if(X == 22)
     { //gramos a libras
int gramos;
cout << "\nEscribe los gramos: ";
cin >> gramos;
cout << "El resultado en libras es " << gramos * 0.00220462 << endl;
  system("pause>nul");

      }

      if(X == 23)
     { //libras a gramos
int libras;
cout << "\nEscribe las libras: ";
cin >> libras;
cout << "El resultado en gramos es " << libras * 453.592 << endl;
  system("pause>nul");

      }

      if(X == 24)
     { //gramos a kilogramos
int gramos;
cout << "\nEscribe los gramos: ";
cin >> gramos;
cout << "El resultado en kilogramos es " << gramos * 0.001 << endl;
  system("pause>nul");

      }

      if(X == 25)
     { //kilogramos a gramos
int kilos;
cout << "\nEscribe los kilogramos: ";
cin >> kilos;
cout << "El resultado en gramos es " << kilos * 1000 << endl;
  system("pause>nul");

      }

      if(X == 26)
     { //libras a kilogramos
int lib;
cout << "\nEscribe las libras: ";
cin >> lib;
cout << "El resultado en kilogramos es " << lib * 0.453592 << endl;
  system("pause>nul");

      }

      if(X == 27)
     { //kilogramos a Libras
int kilos;
cout << "\nEscribe los kilogramos: ";
cin >> kilos;
cout << "El resultado en libras es " << kilos * 2.20462 << endl;
  system("pause>nul");

      }

      if(X == 28)
     { //gramos a toneladas
int gr;
cout << "\nEscribe los gramos: ";
cin >> gr;
cout << "El resultado en toneladas es " << gr * 0.000001 << endl;
  system("pause>nul");
       }

       if(X == 29)
      { //toneladas a gramos
 int t;
cout << "\nEscribe las Toneladas: ";
cin >> t;
cout << "El resultado en gramos es " << t * 1000000 << endl;
   system("pause>nul");
        }

        if(X == 30)
       { //libras a toneladas
  int lb;
cout << "\nEscribe las libras: ";
cin >> lb;
cout << "El resultado en toneladas es " << lb * 0.000453592 << endl;
    system("pause>nul");
         }

         if(X == 31)
        { //toneladas a libras
   int t;
cout << "\nEscribe las toneladas: ";
cin >> t;
cout << "El resultado en libras es " << t * 2204.62 << endl;
     system("pause>nul");
          }

          if(X == 32)
         { //kilos a toneladas
  int kilos;
cout << "\nEscribe los Kilogramos: ";
cin >> kilos;
cout << "El resultado en toneladas es " << kilos * 0.001 << endl;
      system("pause>nul");
           }

           if(X == 33)
          { //toneladas a kilogramos
   int t;
cout << "\nEscribe las toneladas: ";
cin >> t;
cout << "El resultado en kilogramos es " << t * 1000 << endl;
       system("pause>nul");
            }

          if(X == 34)
          {//cronometro beta

            int h,m,s;
  for(h=0; h<12; h++){
    for(m =0; m<60; m++){
    	for(s=0; s<60; s++){
      	cout <<"\t\t\t\t" <<h << ":" << m << ":" << s << endl;
  	Sleep(1000); //aqui vamos a usar el sleep para ver el tiempo , para no verlo tan rapido ni lento sino normal como un conometro
      			//system("cls");//para limpiar la consola (dejarlo en comentario para el historial)
                             }
                       }
                   }
system("pause");
return 0;

          }

          if(X == 35)
          {//cronometro beta
            int h,m,s;
  for(h=0; h<12; h++){
    for(m =0; m<60; m++){
      for(s=0; s<60; s++){
       cout <<"\t\t\t\t" <<h << ":" << m << ":" << s << endl;
    Sleep(1000); //aqui vamos a usar el sleep para ver el tiempo , para no verlo tan rapido ni lento sino normal como un conometro
        system("cls");//para limpiar la consola
                             }
                        }
                    }
system("pause");
return 0;
          }

          if(X == 36)
         { //segundos a minutos
int s;
cout << "\nEscribe los segundos: ";
cin >> s;
cout << "El resultado en minutos es " << s * 0.0166667 << endl;
system("pause>nul");
           }

           if(X == 37)
          { //segundos a horas
int s;
cout << "\nEscribe los segundos: ";
cin >> s;
cout << "El resultado en horas es " << s * 0.000277778 << endl;
system("pause>nul");
            }

            if(X == 38)
           { //segundos a dias
int s;
cout << "\nEscribe los segundos: ";
cin >> s;
cout << "El resultado en dias es " << s * 0.0000115741 << endl;
system("pause>nul");
             }

             if(X == 39)
            { //minutos a segundos
int m;
cout << "\nEscribe los minutos: ";
cin >> m;
cout << "El resultado en segundos es " << m * 60 << endl;
system("pause>nul");
              }

              if(X == 40)
             { //minutos a horas
int m;
cout << "\nEscribe los minutos: ";
cin >> m;
cout << "El resultado en horas es " << m * 0.0166667 << endl;
system("pause>nul");
               }

               if(X == 41)
              { //minutos a dias
int m;
cout << "\nEscribe los minutos: ";
cin >> m;
cout << "El resultado en dias es " << m * 0.000694444 << endl;
system("pause>nul");
                }


    } //fin del programa
} //fin de main()
