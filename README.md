
                                                               UNIVERSIDAD DE GUADALAJARA


                                                CENTRO UNIVERSITARIO DE CIENCIAS EXACTAS E INGENIERÍAS
                                                             INGENIERÍA EN COMPUTACIÓN(INCO)

#   ![1200px-Escudo_UdeG svg(2)](https://user-images.githubusercontent.com/86133272/196335527-b623efcf-04dd-4c40-9843-29dec1ab1eff.png)    ![Escudo_CUCEI svg(1)](https://user-images.githubusercontent.com/86133272/196344534-8bf06142-5fdc-4b7e-a47f-9a9e54896898.png)
               
                                           MATERIA: SEMINARIO DE SOLUCIÓN DE PROBLEMAS DE TRADUCTORES DE LENGUAJES II. 

                                                                   SECCIÓN: D02.

                                                      DOCENTE: Lopez Franco, Michel Emanuel.

                                                           ALUMNO: Izmael Guzmán Murguía.

                                                                 CÓDIGO: 216728179.


                                                               Tarea: Proyecto final.





                                                  FECHA DE ENTREGA: Lunes 5 de diciembre de 2022.




##                                Requerimietnos para la ejecucion
*   Para poder ejecutar el codigo de ensamblador se necesitara nasm.
*   El ensamblador generado es x86 y se ejecuta en __Linux__
*   Puedes probar el compilador en la siguiente direccion (https://vadim01j12feradim.github.io/COMPILE/)
###                                Lo que es capaz de hacer el compilador:
*  Validar retornos.
*  Validar tipos de datos al asignar.
*  Validar retornos de del mismo tipo de el que es la función.
*  Validar retornos.
*  Análisis de gramática.
*  Análisis semántico.
*  Análisis sintáctico.
*  Definición de funciones.
*  Llamada a funciones.
*  Paso de parámetros a funciones.
*  Validación de tipos y cantidad de parámetros en funciones.
*  Definición de variables locales y globales.
###                              Lo que no es capaz de hacer el compilador:
*  Utilizar objetos.
*  Utilizar punteros.
*  Utilizar tipos de datos diferentes a string, int y float.
*  Incluir librerías.
###                               Información que se suministra.
*  Tabla de símbolos.
*  Tabla LR(1) de la gramática.
*  Análisis con pila de enteros.
*  Análisis con objetos.
*  Árbol de análisis gráfico y dinámico.
*  Tabla de variables.
*  Tabla de funciones donde se incluye la función printi y prints por defecto que reciben un parámetro int y string respectivamente, utilice estas funciones para imprimir resultados.
*  Código intermedio.
*  Código en ensamblador.
*  Botón de descarga de fichero con código ensamblador en el que se incluye información como el creador y comando para ejecutar en la terminal para la ejecución del programa.

**Ejemplo e indicaciones.**

1. La página web contiene tres ejemplos de prueba los cuales pueden ser utilizados para comprobar el funcionamiento de el compilador, cuando un programa funciona correctamente la salida es muy parecida a la siguiente.
![Screenshot 2022-10-18 00:44:15](https://user-images.githubusercontent.com/86133272/196357014-fc587b7d-8ff1-4b2b-9d8e-b4c8b50de09b.png)
2. El ejemplo del código número uno es el siguiente.
![Screenshot 2022-10-18 00:57:28](https://user-images.githubusercontent.com/86133272/196357228-2649d7d5-85c6-4b54-82b6-e48356e823ee.png)
3. El código del ejemplo número dos es el siguiente.
 ![Screenshot 2022-10-18 00:58:45](https://user-images.githubusercontent.com/86133272/196357280-8eddda57-b21f-4e7f-b8f4-4a8afb8ad38b.png)
4. Finalmente el código del ejemplo número tres es el siguiente.
![Screenshot 2022-10-18 01:10:21](https://user-images.githubusercontent.com/86133272/196357309-cf6bca6c-e3db-4719-bbc6-653c5df5e3e3.png)
5. Además es posible abrir archivos de texto donde se encuentre nuestro código a compilar.
![Screenshot 2022-10-18 01:12:26](https://user-images.githubusercontent.com/86133272/196357331-a8a497ae-3005-46a3-8d1e-29cbd808beb8.png)
6. Un ejemplo de ejecución es el siguiente, es importante mencionar que para ejecutar el programa debe dar clic en el botón vamos.
![Screenshot 2022-10-18 01:13:21](https://user-images.githubusercontent.com/86133272/196357352-2a8a3d1f-eba4-47c8-bc63-8a6926749564.png)
7. En primer lugar tenemos un botón para desplegar la tabla de símbolos si lo presionamos de nuevo se ocultara la información.
![Screenshot 2022-10-18 01:14:12](https://user-images.githubusercontent.com/86133272/196357385-2da0bb37-585f-4b14-81f6-f3ac21530f91.png)
8. El siguiente botón corresponde a la tabla LR(1) donde se muestra la lógica de la gramática, naturalmente esta tabla no cambia con las ejecuciones.
![Screenshot 2022-10-18 01:15:42](https://user-images.githubusercontent.com/86133272/196357417-0eeb2fd7-2ef0-4dd6-bd0d-443d85af36e4.png)
9. Como siguiente botón tenemos el apartado del análisis con pila de enteros.
![Screenshot 2022-10-18 01:18:23](https://user-images.githubusercontent.com/86133272/196357450-d0dc2f65-d7aa-4a70-ba06-5fc3fb689c73.png)
10. A continuación el análisis con objetos.
![Screenshot 2022-10-18 01:19:32](https://user-images.githubusercontent.com/86133272/196357475-e2ce2251-fec5-4c76-9b13-c9921a342ec7.png)
11. En el siguiente botón tenemos un árbol dinámico resultado del análisis que nos ayudará a entender mejor cómo es que se hace el análisis de desplazamientos y deducciones aplicando las reglas y la tabla de gramática.
![Screenshot 2022-10-18 01:20:10](https://user-images.githubusercontent.com/86133272/196357498-18dccaa0-f376-4e8a-9c43-c5f864f972b3.png)
12. El botón tabla de variables muestra todas las variables declaradas en el programa mostrando el nombre de la variable, el tipo y el ámbito al que pertenece respectivamente.
![Screenshot 2022-10-18 01:21:51](https://user-images.githubusercontent.com/86133272/196357532-ff6035bd-186f-436c-85b2-3239480a95f8.png)
13. El botón Tabla de funciones muestra las funciones que existen en el programa, por defecto se tiene la función printi y prints que reciben un parámetro int y string respectivamente, además se muestra el tipo de dato que regresan.
![Screenshot 2022-10-18 01:23:34](https://user-images.githubusercontent.com/86133272/196357638-ebace8d1-a65c-4754-b02c-d9ce09d49ed7.png)
14. El siguiente botón muestra el código intermedio generado.
![Screenshot 2022-10-18 01:27:00](https://user-images.githubusercontent.com/86133272/196357661-1f8cf5a2-86f9-4aeb-a2db-4dcb54b6ded0.png)
15. El botón código ensamblador muestra el código ensamblador que se generó, este puede ser copiado o utilizar el botón para descargar el archivo .asm.
![Screenshot 2022-10-18 01:29:32](https://user-images.githubusercontent.com/86133272/196357681-62011b2a-1967-402c-9f00-ce452eb8336b.png)
16. Para descargar el archivo .asm presione el botón descargar código ensamblador.
![Screenshot 2022-10-18 01:30:13](https://user-images.githubusercontent.com/86133272/196357742-4af40c6e-da77-4c19-a5dc-7a951d6ab4ed.png)
17. Si abrimos el archivo este contendrá el código ensamblador y en las primeras dos líneas los comandos posibles para ejecutar el ensamblador, elija el que más se adecue a sus necesidades.
![Screenshot 2022-10-18 01:32:51](https://user-images.githubusercontent.com/86133272/196357766-289115c0-33a8-496e-ae3a-91b8ce9c88ef.png)
18. Para ejecutarlo habrá una terminal en la ubicación donde se encuentra su archivo code.asm y ejecute el comando de ejecución.
![Screenshot 2022-10-18 01:34:48](https://user-images.githubusercontent.com/86133272/196357786-f81cd3ac-714f-42f3-9197-206f50733510.png)
Esto es todo :).

