# imt2200_actividad1
## María Paz Allendes Álvarez
### Contenidos del Repositorio:
- Archivo .gitignore, creado para evitar subir archivos temporales.
- Mapas y DataFrame de los datos del Censo 2017
### Cambios y mejoras:
- En primer lugar, creé un nuevo DataFrame que muestra las regiones ordenadas de mayor a menor según la cantidad de personas.
- Luego, usé dat.info para verificar si el dataset contenía datos sobre las regiones, como sus nombres. Al confirmar que sólo existían códigos numéricos para las regiones, creé un diccionario que asigna a cada código su nombre correspondiente. Con este diccionario, generé otro DataFrame que incluye el nombre de la región junto con la cantidad de personas, ordenado de mayor a menor junto con su mapa correspondiente.
- Respecto a la visualización, modifiqué el gráfico de distribución de población por edad y región cambiando los colores y el tamaño de la figura (figsize). Además, creé dos gráficos adicionales con el mismo conjunto de datos, usando los tipos area y hist, respectivamente.
- En cuanto al mapa con información del censo, cambié el color a cyan y mostré las primeras tres líneas del DataFrame con head(3).
- Finalmente, en el mapa de población total por manzana, ajusté los colores, modifiqué el espacio de la barra de color, cambié la posición de la leyend poniéndola abajo y la barra de colores la coloqué a la izquierda, para mejorar la presentación visual.
