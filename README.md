# Segunda Práctica de Visión por Computador

## Inicializacion 

Zona destinada a inicializar algunos valores necesarios para las tareas.

## TAREA: Realiza la cuenta de píxeles blancos por filas, determina el máximo para filas y columnas (uno para cada) y muestra el número de valores que superan en cada caso 0.95*máximo.

Para realizar esta tarea usaremos la funcion cv2.reduce pero esta vez en dos dimensiones para también poder hacer el calculo por columnas, después añadimos los datos dados por la funcion a una lista y la mostramos.


## TAREA: Elige otra imagen, muestra el contenido de alguna de las imágenes resultado de Sobel antes y después de ajustar la escala



## TAREA: Aplica umbralizado a la imagen resultante de Sobel (valores 0 a 255 y convertida a 8 bits por ejemplo sobel8 = np.uint8(sobel)), y posteriormente realiza el conteo por filas y columnas similar al realizado en el ejemplo con la salida de Canny. Calcula los máximos por filas y columnas, y determina las filas y columnas por encima del 0.95*máximo. Remarca con alguna primitiva gráfica dichas filas y columnas sobre la imagen ¿Cómo se comparan los resultados obtenidos a partir de Sobel y Canny?


## TAREA: Asumiendo que quieren mostrar a personas que no forman parte del curso de VC el comportamiento de una o varias funcioens de las vistas hasta este momento aplicadas sobre la entrada de la webcam. ¿Cuál(es) escogerían?

En nuestro caso hemos escogido el pop-art de la practica anterior debido a su gran llamativo visual y por otro lado la eliminacion de fondo también debido a que creemos que es lo que mas interes podria levantar para gente que no entiende cursa la asignatura. 

## TAREA: Tras ver los vídeos My little piece of privacy, Messa di voce y Virtual air guitar propongan (los componentes de cada grupo) una reinterpretación del procesamiento de imágenes con las técnicas vistas o que conozcan.
