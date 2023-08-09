# classification-tree

Modelo de ML de arbol de clasificación para la prediccion del exito de la campaña de marketing de una entidad bancaria
Este notebook contiene un análisis exploratorio y construcción de un árbol de decisión sobre un conjunto de datos de marketing bancario.

## Datos

El conjunto de datos se llama BankMarketing.csv y contiene información sobre campañas de marketing directo de una institución bancaria. Incluye variables demográficas, de productos y de campañas.

## Análisis exploratorio

Se realiza un análisis exploratorio de los datos para identificar:

* Datos faltantes
* Valores atípicos
* Distribución de variables continuas y categóricas
* Correlación entre variables y clase objetivo

## Construcción del modelo
Se construye un árbol de decisión para predecir si un cliente contratará o no un depósito bancario (y). El árbol tiene las siguientes especificaciones:

Profundidad máxima de 4
Tamaño mínimo de hoja de 25 instancias
Se grafica el árbol con graphviz para visualizarlo.

## Resultados
El modelo logra una exactitud de 78% en el conjunto de prueba.
