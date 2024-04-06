Pila y Cola

Pila: Pila de Platos Sucios

Este es un programa Java que simula una pila de platos sucios y proporciona
funcionalidades para agregar platos sucios, lavar el plato superior,
ver el plato superior, verificar si la pila está vacía y buscar un plato en la pila.

Funcionalidades
1.Agregar un plato sucio a la pila: Permite al usuario agregar un plato sucio a la pila.
2.Lavar el plato superior de la pila: Lava el plato superior de la pila si hay platos sucios disponibles.
3.Ver el plato superior de la pila: Muestra el plato superior de la pila sin eliminarlo.
4.Verificar si la pila está vacía: Informa al usuario si la pila de platos está vacía o no.
5.Buscar un plato en la pila: Permite al usuario buscar un plato específico en la pila y devuelve su posición relativa desde la parte superior de la pila.
6.Salir: Termina la ejecución del programa.

El programa simula una pila de platos sucios utilizando la clase Stack de Java. 

1. Inicialización de la pila y del scanner: Se crea una nueva instancia de Stack<String> para almacenar los platos sucios.
También se crea un objeto Scanner para leer la entrada del usuario desde la consola.
2. Menú de opciones: Se muestra un menú con varias opciones que el usuario puede elegir.
Estas opciones incluyen agregar un plato sucio a la pila, lavar el plato superior, ver el plato superior,
verificar si la pila está vacía, buscar un plato en la pila y salir del programa.
3. Selección de opción y ejecución: El programa solicita al usuario que ingrese una opción del menú.
Dependiendo de la opción seleccionada por el usuario, se ejecuta el bloque de código correspondiente.
4. Agregar un plato sucio: Se solicita al usuario que ingrese el nombre del plato sucio y se agrega a la pila utilizando el método push().   
5. Lavar el plato superior: Se verifica si la pila no está vacía y se limpia el plato superior utilizando el método pop().
6. Ver el plato superior: Se muestra el plato superior de la pila sin eliminarlo utilizando el método peek().
7. Verificar si la pila está vacía: Se verifica si la pila está vacía utilizando el método isEmpty() y se informa al usuario.
8. Buscar un plato en la pila: Se solicita al usuario que ingrese el nombre del plato a buscar y se utiliza el método search()
para encontrar la posición relativa del plato en la pila.
9. Salir del programa: Se establece la variable salir en true para salir del bucle while y terminar la ejecución del programa.
10. Finalización del programa: Una vez que el usuario elige salir del programa, se muestra un mensaje de despedida y el programa termina su ejecución.

Cola: Cola de Banco

Este es un programa Java que simula una cola de atención en un banco. Proporciona funcionalidades para agregar clientes a la cola,
atender al próximo cliente, ver al próximo cliente en la cola, verificar si la cola está vacía y salir del programa.

Funcionalidades
1. Agregar cliente a la cola de atención: Permite al usuario agregar un cliente a la cola de atención del banco.
2. Atender al próximo cliente en la cola: Atiende al próximo cliente en la cola y lo elimina de la misma.
3. Ver al próximo cliente en la cola: Muestra al próximo cliente en la cola sin eliminarlo.
4. Verificar si la cola de atención está vacía: Informa al usuario si la cola de atención está vacía o no.
5. Salir: Termina la ejecución del programa.

El programa simula una cola de atención en un banco utilizando la clase Queue y la implementación 
LinkedList de Java. Aquí está el flujo general del programa:

1. Inicialización de la cola y del scanner: Se crea una nueva instancia de Queue<String>
utilizando LinkedList para representar la cola de atención. También se crea un objeto Scanner para leer la entrada del usuario desde la consola.
2. Menú de opciones: Se muestra un menú con varias opciones que el usuario puede elegir. Estas opciones incluyen agregar un cliente a la cola de atención,
 atender al próximo cliente, ver al próximo cliente en la cola, verificar si la cola está vacía y salir del programa.
3. Selección de opción y ejecución: El programa solicita al usuario que ingrese una opción del menú.
Dependiendo de la opción seleccionada por el usuario, se ejecuta el bloque de código correspondiente.
4. Agregar cliente a la cola de atención: Se solicita al usuario que ingrese el nombre del cliente y se agrega a la cola utilizando el método add().
5. Atender al próximo cliente: Se verifica si la cola no está vacía y se atiende al próximo cliente en la cola utilizando el método poll()
que también lo elimina de la cola
6. Ver al próximo cliente en la cola: Se muestra al próximo cliente en la cola sin eliminarlo utilizando el método peek().
7. Verificar si la cola está vacía: Se verifica si la cola está vacía utilizando el método isEmpty() y se informa al usuario.
8. Salir del programa: Se establece la variable salir en true para salir del bucle while y terminar la ejecución del programa.
9. Finalización del programa: Una vez que el usuario elige salir del programa, se muestra un mensaje de despedida y el programa termina su ejecución.
