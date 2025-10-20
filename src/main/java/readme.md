# 🔍 Comparación de Rendimiento entre Listas y Sets en Java

Este proyecto en **Java** compara el **rendimiento de diferentes implementaciones de colecciones** (List y Set) al realizar operaciones comunes como **añadir, eliminar, buscar y recorrer elementos**.

El objetivo es observar cómo varían los tiempos de ejecución entre estructuras como `ArrayList`, `LinkedList`, `HashSet` y `TreeSet` cuando se manejan grandes volúmenes de datos (2.000.000 de elementos).



💡 Conclusiones Esperadas

ArrayList suele ser más rápido en añadir y recorrer elementos secuencialmente.

LinkedList puede ser más lento debido a su estructura enlazada.

HashSet es muy eficiente para búsqueda y eliminación, pero no mantiene orden.

TreeSet mantiene los elementos ordenados, pero a costa de menor velocidad.


🧰 Tecnologías Utilizadas

Java SE 17+

API de colecciones (java.util)

java.time.Instant y Duration para medir tiempos de ejecución