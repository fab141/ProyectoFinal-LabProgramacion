# ProyectoFinal-LabProgramacion
Programación del juego clásico PacMan en python usando la librería Pygame. Creado por Faustin Acuña Burgos - B90054


#------ DESCRIPCIÓN GENERAL  --------

El juego está desarrollado usando la librería Pygame. 
Las imagenes del Pacman, los fantasmas (Clyde, Pinky, Inky, Blinky) fueron tomadas de la web.

En el archivo board.py se establecen las configuraciones iniciales del tablero:
 - Distribución de puntos
 - Distribución de poderes
 - Distribución de las trayectorias que sigue el pacman y los fantasmas.

Todo en modo de un array.

En el archivo principal pacman.py se desarrolla todo el juego.

En la primera parte se definen la clase fantasma que contiene

 - Atributos como la posición, velocidad, contadores de colisión de cada fantasma.
 - Los métodos para moverse, verificar colisión y cambiar de estado.

Después se define la clase jugador que contiene

 - Atributos como la posición, velocidad, contadores de colisión para el pacman.
 - Los métodos para moverse, verificar colisión y cambiar de estado, comer puntos, etc

Por último se ejecuta el juego en un bucle While para jugar indefinidamente hasta que el jugador desee salir de la ventana, durante la ejecución se ejecutan los métodos y las funciones definidas en las clases.
