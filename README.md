# Laboratorio 6
# Simulación de Navegador Web con Historial

Este codigo fue desarrollado en lenguaje C para simular el comportamiento de un navegador web, gestionando el historial de navegación mediante una estructura tipo pila.

#----Instrucciones de uso----#

Se presenta un menu principal donde se va realizar el proceso del programa: 
1. Visitar nueva página  
   - Permite ingresar la URL de una nueva página.  
   - Se guarda en la pila y se convierte en la página actual.  

2. Atrás  
   - Regresa a la página anterior.  
   - Elimina la página actual de la pila (disminuye la cima).  

3. Mostrar historial  
   - Muestra todas las páginas almacenadas en la pila.  
   - Se visualizan desde la más reciente hasta la más antigua.  

0. Salir  
   - Finaliza la ejecución del programa.

## Estructuras utilizadas

- Se utilizó un arreglo bidimensional `pila[50][100]` para almacenar hasta 50 URLs, cada una de hasta 100 caracteres.
- La variable `cima` funciona como puntero a la última página activa, implemnetada de la pila.
- Se usaron condicionales `if` y estructuras de repetición `do-while` para el menú principal.

## Lo aprendido

- Cómo simular una **pila (LIFO)** en lenguaje C usando un arreglo.
- El uso de cadenas (`char[][]`) para almacenar texto, en este caso las URLs.
- El uso de `scanf(" %[^\n]", ...)` para leer cadenas con espacios.
- Manejo del historial como una estructura de navegación realista, el como ir atrás, mostrar historial, y otros.

