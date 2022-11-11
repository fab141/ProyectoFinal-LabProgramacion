# ProyectoFinal-LabProgramacion
Programación del juego clásico PacMan en python usando la librería Pygame. Creado por Faustin Acuña Burgos - B90054


------ DESCRIPCIÓN GENERAL  --------

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

Según el desarrollo del proyecto, a criterio personal del estudiante, se propone en la siguiente tabla la evaluación
![Screenshot from 2022-11-11 14-15-59](https://user-images.githubusercontent.com/118016955/201414127-d4c03dbb-6389-4e44-a1af-38142dc49401.png)

**Comentarios adicionales:** La interfaz gráfica es bastante similar a la del juego original, en cuanto a personajes, colores, reglas de juego y controles. Los efectos visuales fueron implementados casi en total igualdad al juego original, sin embargo alguno efectos de sonido no fueron implementados por complejidad de código como por ejemplo efectos de sonido al obtener un poder, perder una vida o ganar el juego. Sin embargo la tradicional melodía al inciar el juego fue implementada. Los controles por teclado, por la esencia misma del juego, son bastante simples y solo se requiere de las teclas derecha, izquierda, arriba y abajo para jugarlo; esto favorece también la experiencia de usuario. La estructura del código fue un poco extensa, pero a su vez es fácil de entender ya que utiliza estructuras básicas de python como condicionales y bucles a lo largo de todo el código además de los comandos especiales de la librería Pygame para ejecutar las animaciones.
