# VC_P1
Primera práctica de Visión por Computador

## TAREA: Sin herramientas de IA, crea una imagen, p.e. de 800x800 píxeles, con la textura del tablero de ajedrez. Una vez resuelto de forma manual, resuelve la misma tarea usando un asistente de IA de tu elección (Claude, ChatGPT, Copilot, etc.). Compara ambas versiones en el informe de la práctica.

En primer lugar se ha creado un algoritmo sencillo para dibujar un tablero de ajedrez con un bucle for, recorriendo toda la imagen y dibujando solo cuando es conveniente.
Por otro lado, Copilot ha decidido mejorar haciendo uso de operaciones vectorizadas de NumPy para no recorrer pixeles manualmente.

## TAREA: Crear una imagen estilo Mondrian (un ejemplo https://www3.gobiernodecanarias.org/medusa/ecoescuela/sa/2017/04/17/descubriendo-a-mondrian/) con las funciones de dibujo de OpenCV. No hagas uso de herramientas de IA, parte del ejemplo anterior.

La imagen ha sido creada haciendo uso de OpenCV con sus funciones line y rectangle. 

## TAREA: Pintar círculos en las posiciones del píxel más claro y oscuro de cada fotograma captado por la cámara. ¿Funciona de forma fluida o a saltos? En el segundo caso, ¿podrías acelerarlo? Si haces uso de herramientas de IA, incluye la conversación.

Se ha desarrollado un código sencillo en el que los pixeles se dibujan con saltos y con la ayuda de Copilot se ha mejorado la solución utilizando areas de 8x8 pixeles, haciendo mas fluido el dibujado de los pixeles.

## TAREA: Llevar a cabo una propuesta propia de pop art. Incluye fuentes consultadas. Si haces uso de herramientas de IA, incluye la conversación.

La propuesta recoge dos estilos nacidos de la prueba y error con los canales de color y dos recomendaciones de Copilot.
