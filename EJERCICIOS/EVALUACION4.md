# Práctica 4.

## 4. SENTENCIAS

Objetivo: Verificar el dominio teórico y técnico del concepto de sentencias en el lenguaje
de java mediante ejercicios para desarrollar su código.
Indicaciones: Pedir responder cada una de las preguntas de manera breve y clara.

1. El siguiente código contiene una clase Pedido para realizar un seguimiento de los
envíos de compras a minoristas. (Valor 5 puntos)

                  public class Pedido {
                    public static void main(String[] args) {
                      double costoArticulo = 30.99;
                      boolean listoEviar=false;
                      
                      if (costoArticulo > 24.00)
                      {
                        System.out.println("¡El valor del articulo es alto!");
                     
                     if (listoEviar ==true) 
                     {
                        System.out.println("Enviado");
                     }
                     else
                     {
                        System.out.println("Pedido no listo");
                     }
                     }
                     
                    }
                  }

a. Escribe una declaración usando if que imprima ¡El valor del artículo es alto!
cuando costoArticulo es mayor que 24.00.

b. En el código de arriba hay variable listoEnviar cuyo valor representa si el pedido
está listo para enviarse. Escribe un enunciado if-then-else que:

● Cuando listoEnviar sea verdadero (true), imprima Enviado.

● Cuando listoEnviar sea falso (false), imprima Pedido no listo.

Salida:

            ¡El valor del articulo es alto!
            Pedido no listo

2. Realiza un programa en java que imprima los primeros 15 elementos de alguna de
las siguientes series haciendo uso necesariamente de las sentencias de control:
(Valor 5 puntos)

● Serie de números impares positivos

1, 3, 5, 7, 9, 11, 13, 15, 17, .... así sucesivamente.

                                               public class SerieImp{
                                                  public static void main(String[] args) {

                                                  int n=15;

                                                  for (int i=1; i<=n; i++)
                                                  {
                                                      if(i%2==1)
                                                      {
                                                          System.out.print(i+ ",");
                                                      }
                                                  }

                                                  }

                                              }



● Serie de Fibonacci

0, 1, 1, 2, 3, 5, 8, 13, 21, 34, ... así sucesivamente.

                                          public class SerieFibonacci{
                                              public static void main(String[] args){

                                                  int i=1;
                                                  int n=15;
                                                  int primerTermino=0;
                                                  int segundoTermino=1;

                                                  while (i<=n){
                                                      System.out.print(primerTermino + ", ");
                                                      int terminoActual=primerTermino + segundoTermino;
                                                      primerTermino=segundoTermino;
                                                      segundoTermino=terminoActual;
                                                      i++;
                                                  }
                                              }

