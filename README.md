# Primera Práctica de Visión por Computador

Para la realización de la práctica hemos desarrollado mas de una solución para la mayoria de las tareas.

## Inicializacion 

Zona destinada a inicializar algunos valores necesarios para las tareas.

## TAREA: Crea una imagen, p.e. 800x800, con la textura del tablero de ajedrez

Para crear el tablero 8x8 del ajedrez aprovechamos que tenemos el fondo de la imagen ya inicializado a una imagen negra para dibujar solo las casillas blancas. Para dibujar estas casillas, en las iteraciones pares de nuestro bucle for cambiaremos la coordenada en la que comenzamos a dibujar por la segunda casilla y en las impares volveremos a dibujar en la casilla mas a la izquierda, consiguiendo asi la "red" caracteristica del tablero de ajedrez.

## TAREA: Resuelve una de las tareas previas (a elegir) con las funciones de dibujo de OpenCV  :)



## TAREA: Modifica de alguna forma los valores de un plano de la imagen

Para modificar los valores del plano de imagen, capturamos la imagen de la camara y separamos cada plano y jugamos con ellos, primer lugar mostramos el campo rojo y azul invertidos y en segundo lugar quitamos todos los planos y dejamos una escala de grises y blancos.

## TAREA: Pintar círculos en las posiciones del píxel más claro y oscuro de la imagen ¿Si quisieras hacerlo sobre la zona 8x8 más clara/oscura?

Para poder pintar los circulos en los pixeles mas claros y oscuros, capturaremos la camara como hicimos en el caso anterior y pasaremos el frame a una escala de grises para utilizar proximamente la funcion minMaxLoc que nos dara el maximo y minimo local el que dibujaremos la esfera.

## TAREA: Haz tu propuesta pop art

Para la propuesta pop art simplemente manipulamos algunos planos capturados por camara y lo mostramso en viñetas de 4.
