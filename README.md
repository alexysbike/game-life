# Juego de la Vida (Conway)

[Demo](https://alexysbike.github.io/game-life/index.html)

### Informacion:
Implementacion del algoritmo de Conway: Juego de la Vida

### Caracteristicas:

* Renderizado en CANVAS HTML5.
* Seguimiento en vivo del numero de iteraciones y de celulas vivas, ademas del estado de ejecucion.
* Botones de Play/Pausa, Iterar 1 vez, Reinicio y Grafica de Evolucion de Celulas Vivas.
* Configuracion del Tamano de la celula, cantidad de filas y columnas y una constante que influye en la cantidad aleatoria inicial de las celulas vivas.
* Control de las iteraciones por segundo del juego.
* Modificacion de los colores de las celulas vivas y muerta, ademas de las lineas divisorias haciendo uso del colorpicker.
 
Se hace uso de Canvas HTML5 para el renderizado de los graficos del Juego de la Vida y del Grafico evolucion de Celulas Vivas, usando tecnicas para mejorar el rendimiento y asi poder tener mayor numero de celulas y mayor velocidad (Iteraciones por segundo), se puede tener una excelente ejecucion de un tablero de 50x80 celulas a 30 iteraciones por segundo. Ademas el llenado inicial aleatorio fue ajustado para generar una cantidad de celulas vivas estables y se puede modificar en la interfaz. El codigo responsable del funcionamiento del juego y de la grafica esta hecho sin el uso de ningun tipo de framework (solo js nativo), haciendo uso de tecnicasde programacion orientada a objetos mejorando el rendimiento total del codigo. Se uso bootstrap para estilizar la interfaz y se uso un plugin externo para el "Color Picker" en las opciones de colores del lienzo.