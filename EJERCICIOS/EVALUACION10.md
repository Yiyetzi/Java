# Práctica 10.

10. COLAS

Objetivo: Verificar el dominio teórico y técnico del uso y manipulación de colas en java
mediante ejercicios para desarrollar su código, preguntas de respuesta múltiple y
abiertas.

Indicaciones: Pedir responder cada una de las preguntas de manera breve y clara.

1. ¿Las operaciones FIFO (First In, First Out), son características de las colas en
programación? (Valor 1 punto)

              a. Verdadero
          

2. Se tiene la siguiente lista con 6 elementos, teniendo en cuenta que es una cola
contesta lo siguiente: (Valor 1 punto)

            a. ¿Cuál fue el último elemento en entrar? 5
            b. ¿Cuál fue el primer elemento en salir? 8

![image](https://user-images.githubusercontent.com/91554777/181846519-d3a5f664-1e13-4f1d-be3d-30d232fb5f2e.png)

3. ¿Qué método no se utiliza para remover un elemento de la cola? (Valor 1 punto)

            a. peek()
           

4. ¿Para qué sirven los métodos peek() y element() en las colas? (Valor 1 punto)

            b. Para recuperar o buscar el elemento de la cabecera de la cola y no imprime
            los elementos que tiene.
            

5. Se quiere agregar un elemento a una cola, cuál o cuáles son las sintaxis correctas
para hacerlo: (Valor 1 punto)

              a. variable.add(“Perro”)
             
              c. variable.offer(“Perro”)
            
             

6. Escribe un programa en java con las siguientes indicaciones: (Valor 3 puntos)

a. Importa las clases necesarias para construir una cola.

b. Crea una cola llamada usuarios y agrega 5 nombres de tus compañeros de
clase.

c. Una vez agregados, elimina 3 elementos de la cola e imprime el mensaje El
nombre a eliminar es: “Nombre a eliminar”.

i. Ejemplo. El nombre a eliminar es: Nombre 1.

d. Finalmente, imprime otro mensaje que diga: El próximo nombre a eliminar
es: “Nombre a eliminar”.

i. Ejemplo. El próximo nombre a eliminar es: Nombre 4.

            import java.util.Queue;
            import java.util.LinkedList;

            /**
             *
             * @author linux
             */
            public class Evaluacion10 {

                public static void main(String[] args) {
                Queue<String>usuarios = new LinkedList<>();

                usuarios.add("Francisco");
                usuarios.add("Fernanda");
                usuarios.add("María");
                usuarios.add("Alfonso");
                usuarios.add("Yiyetzi");

                usuarios.remove();
                usuarios.remove();
                usuarios.remove();

                    System.out.println("El nombre a eliminar es: "  + usuarios.remove());
                    System.out.println("El próximo nombre a eliminar es: "  + usuarios.remove());

                }
            }

