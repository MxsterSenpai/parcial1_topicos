# Parcial #1 de tópicos especiales

## Problema #1: Filtros y Detectores
En esta sección se utilizará el archivo Problema1.jpg. Cargue la imagen indicada en su programa. Deberá aplicar a esta imagen una serie de filtros de la siguiente manera.

    1.	Cree una copia de la imagen original y aplique un filtro de Gauss de tamaño 25 × 25.

    2.	Cree una copia de la imagen y aplique un filtro bilateral con diámetro de 39.

    3.	En este punto tendrá 3 imágenes (original, Gauss y Bilateral).

    4.	Aplique a cada una de estas imágenes el detector MSER y genere el resultado con las regiones identificadas para cada imagen, las regiones deben ser marcadas con colores diferentes. En esta detección trate de enfocarse en detectar las letras contenidas en la imagen.

    5.	Una vez creadas las imágenes de las regiones, agregue a cada una un texto con su nombre en la posición (10, 100) y con la cantidad de regiones identificadas, en la posición (2000, 1300) de la imagen, utilizando la función presentada en la sección 0.1. Cambie también el color de la fuente a uno de su agrado.
    
    6.	Presente una matriz utilizando matplotlib con las 6 imágenes generadas adecuadamente rotuladas.

    7.	Agregue el código para que se almacene esta matriz en su computadora, con el nombre” Nombre Apellido P1.png”, adjunte esta imagen en su PDF de resultados.

    8.	Agregue el código para que se visualice el resultado en tiempo de ejecución.

## Problema #2: Transformada de Hough
En esta sección se utilizará el archivo Problema2.jpg. Cargue la imagen indicada en su programa (debe ser a continuación del código del problema anterior). En este caso se aplicará la Transformada de Hough para identificar Círculos en la imagen indicada.

    1.	Cargue la imagen en su código. 

    2.	Agregue a esta imagen un texto con su correo institucional en la esquina inferior izquierda de la imagen, utilizando la función presentada en la sección 0.1. Cambie también el color y la fuente a uno de su agrado. 

    3.	Aplique el algoritmo de Hough para detectar la mayor cantidad de círculos en la imagen, debe identificar al menos 15 círculos en la imagen. 

    4.	Pinte cada círculo detectado con un contorno en un tono verde de su agrado e indique su centro en color rojo. 

    5.	Agregue a cada círculo el número que le corresponde en la lista de detectados. 

    6.	Recorte cada círculo detectado en la imagen y muestre el resultado en una matriz, utilizando subplot de matplotlib, se recomienda utilizar un número de columnas predefinido y un número de filas dinámico. 

    7.	Almacene esta matriz en su computadora (se debe incluir en el PDF) y agregue el código para que se visualice en tiempo de ejecución. Utilice el nombre” Nombre Apellido P21.png”. 

    8.	De igual manera almacene la imagen original con los círculos identificados (se debe incluir en el PDF) y agregue el código para que se visualice en tiempo de ejecución. Utilice el nombre” Nombre Apellido P22.png”. 

    9.	Se recomienda que limite su bucle de recorte y visualización de círculos a un máximo de 40 − 50 para evitar saturar la memoria y también la demora del procesamiento. 

    10.	Consulte la documentación de la función para encontrar la combinación de parámetros más adecuada para la imagen1. 

    11.	Utilizando los círculos detectados, calcule el histograma RGB para cada uno y presente estos histogramas en una matriz similar a la de los recortes de los círculos, utilizando subplot. 

    12.	Identifique cada histograma con un título que contenga el número de circulo correspondiente. 

    13.	Esta matriz debe mostrar adecuadamente cada histograma evitando el solapamiento entre gráficas. Almacene esta matriz en su computadora (se debe incluir en el PDF) y agregue el código para que se visualice en tiempo de ejecución. Utilice el nombre” Nombre Apellido P23.png”. 

    14.	Para esta sección deberá agregar en su PDF 3 imágenes, Nombre Apellido P21.png:

        a.	 Imagen con los círculos marcados y correo del autor. 

        b.	Nombre Apellido P22.png: Matriz de Círculos Detectados. 

        c.	Nombre Apellido P23.png: Matriz de los histogramas de los Círculos Detectados.

## Problema #3: Procesamiento en tiempo real
En esta sección se utilizará una cámara como entrada de imágenes a la computadora, recuerde que en ausencia de la cámara puede utilizar un vídeo como fuente de imágenes. 

    1.	Configure el código fuente para trabajar con cámaras. 

    2.	Tome una copia de cada frame que llega como entrada al sistema, esta copia deberá tener unas dimensiones en ancho y largo de 45 % de la imagen de entrada original. 

    3.	Aplique el detector ORB sobre la copia de la imagen escalada. 

    4.	Dibuje los keypoints detectados en la imagen escalada. 

    5.	Coloque la imagen escalada con los keypoints marcados y ubique la sobre la esquina superior derecha de la imagen. 
    
    6.	Permita que el sistema guarde la captura actual, al presionar una tecla. 

    7.	Presente una captura de pantalla de su ejecución usando la cámara Agregue esta captura a su pdf de resultados.
