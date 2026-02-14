# Practica-Blender-Poligono-Flor
Aquí se muestran las prácticas de la materia de Graficación. Poligono en Blender y la Flor de vida

##Práctica: Generación de Polígonos con Python en Blender

En esta práctica desarrollé un script en Python para crear un polígono regular dentro de Blender. En lugar de modelarlo manualmente con las herramientas del programa, la figura se construye a partir de cálculos matemáticos que determinan la posición exacta de cada punto.

El objetivo fue comprender cómo la geometría y la programación pueden trabajar juntas para generar formas en un entorno tridimensional de manera automática y precisa.

¿Cómo funciona?

El proceso comienza limpiando la escena para asegurar que cada ejecución inicie en un espacio vacío. Esto permite observar claramente el resultado sin interferencias de objetos anteriores.

Después se calculan los vértices del polígono. Para que la figura sea regular, se divide el círculo completo (360 grados) entre el número de lados deseados. Con apoyo de funciones trigonométricas como el seno y el coseno, se determinan las coordenadas de cada punto en el plano.

Una vez obtenidos los puntos, se crean las conexiones entre ellos para formar las aristas y cerrar la figura correctamente.

Finalmente, toda esta información matemática se transforma en una malla dentro de Blender, generando un objeto 3D visible que representa el polígono completo.

¿Qué aprendí?

En esta práctica comprendí cómo aplicar la trigonometría en un contexto real, específicamente en la generación de geometría dentro de un entorno 3D.

También aprendí a utilizar Python como herramienta de automatización en Blender, lo que permite crear estructuras de forma más eficiente que mediante modelado manual.

Reforcé conceptos de lógica de programación, especialmente el uso de ciclos para generar patrones repetitivos de manera estructurada.

Además, entendí la importancia de documentar y respaldar proyectos utilizando GitHub, ya que no solo permite guardar el trabajo, sino también organizar y presentar el proceso de aprendizaje de manera profesional.


##Práctica: Flor de vida con Python en Blender

En esta práctica trabajé en Blender utilizando Python para crear automáticamente un patrón de círculos concéntricos. El objetivo fue entender cómo las matemáticas, especialmente la trigonometría, pueden usarse para organizar objetos en el espacio 3D de manera precisa y ordenada.

Al iniciar, el programa limpia la escena para que cada ejecución empiece desde cero. Esto es importante porque evita que se acumulen objetos de intentos anteriores y permite ver claramente los resultados de cada prueba.

Después se controlan ciertos valores que determinan cómo se distribuyen los círculos alrededor de los 360 grados. Aquí es donde realmente se nota la diferencia: si el ángulo de separación es pequeño, se generan más círculos y el diseño se ve más cerrado o denso. En cambio, si el ángulo es mayor, hay menos círculos y el patrón se ve más abierto y espacioso.

Para colocar los círculos en su posición correcta, se utilizan coordenadas polares. En lugar de decidir directamente las posiciones en el eje horizontal y vertical, se parte de un radio y un ángulo. Luego, mediante funciones trigonométricas como el seno y el coseno, esos valores se transforman en posiciones dentro del espacio 3D.

¿Qué aprendí en esta práctica?

En esta actividad aprendí que las matemáticas no son solo teoría, sino que tienen aplicaciones muy prácticas en el diseño y la programación. Entendí mejor cómo funcionan las coordenadas polares y cómo se pueden convertir en posiciones reales dentro de un entorno tridimensional.

También comprendí la importancia de modificar parámetros para experimentar con distintos resultados visuales. Cambiar un solo valor puede transformar completamente el diseño final.

En general, esta práctica me ayudó a ver cómo se conectan la programación, la geometría y el modelado 3D, y cómo se pueden usar de forma creativa para generar patrones de manera automática.
