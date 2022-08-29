#Práctica 5.

###INSTRUCCIONES

Objetivo: Verificar el dominio teórico y técnico del concepto de la sentencia switch
en el lenguaje de java mediante, preguntas abiertas, de opción múltiple y ejercicios para
desarrollar su código.

Indicaciones: Pedir responder y/o desarrollar cada una de las preguntas de manera
breve y clara.

1. ¿Cuál es la sintaxis de la estructura switch - case en Java? (Valor 2)

            switch (expresion){
            case valor1:
            //codigo
            break;
            case valor2:
            //codigo
            dreak;
            ...
            default:
            //declaraciones predeterminadas
            
            }

2. ¿Cual de las siguientes oraciones es correcta acerca del default dentro de la
estructura switch - case? (Valor 1)

      a. Se ejecuta si el resultado de la expresión no coincide con ningún caso.
   
      
3. ¿Cuál es una afirmación incorrecta de la estructura switch – case? (Valor 1)


        c. El valor para un case debe ser del mismo tipo de datos que la variable en el
        switch.
        
     
4. ¿Qué líneas del siguiente código tienen algún error? (Valor 2)

![image](https://user-images.githubusercontent.com/91554777/176980099-2bf4ede3-0c22-49af-9bc5-0d2f09f81976.png)

       c) Línea 1, 9 10, 14
      
 5. En la estructura switch - case, ¿cuál instrucción se usa para terminar la secuencia
de un caso? (Valor 1)

      
      c. break
      
      
6. Crea el código en java bajo las siguientes instrucciones: (Valor 3)

        a. Importa la clase Scanner para la lectura de datos.
        b. Crea un objeto semana de la clase Scanner.
        c. Crea una variable dia de tipo entero.
        d. Imprime el texto Introduce un número del 1 al 7 para conocer el día de la
        semana, para hacer la lectura de el dato desde teclado y almacenarlo en la
        variable dia.
        e. Crea una estructura switch-case, donde la variable a comparar con todos los
        casos es dia.
        f. En cada caso, coloca e imprime cada día de la semana (comenzando el Lunes).
        g. Si se ingresa un número de día no válido, imprime el mensaje Número no
        válido.
        
                                    import java.util.Scanner;

                                    public class Evaluacion5 {

                                        public static void main(String[] args) {
                                            Scanner semana = new Scanner(System.in);
                                            int dia;

                                           System.out.println("Introduce un numero del 1 al 7 para conocer el dia de la semana");
                                           dia= semana.nextInt();

                                           switch (dia)
                                           {
                                               case 1:
                                                   System.out.println("Lunes");
                                                   break;

                                               case 2:
                                                   System.out.println("Martes");
                                                   break;

                                                case 3:
                                                   System.out.println("Miercoles");
                                                   break;

                                                 case 4:
                                                   System.out.println("Jueves");
                                                   break;

                                                 case 5:
                                                   System.out.println("Viernes");
                                                   break;

                                                 case 6:
                                                   System.out.println("Sabado");
                                                   break;

                                                 case 7:
                                                   System.out.println("Domingo");
                                                   break;

                                                 default:
                                                     System.out.println("Numero no valido");
                                           }
                                        }
                                    }

