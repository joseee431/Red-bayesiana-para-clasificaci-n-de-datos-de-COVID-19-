# Red-bayesiana-para-clasificaci-n-de-datos-de-LENTES-Y-DE-COVID-19-DE-LA-CDMX
Consiste en la construcción de un modelo de red bayesiana basado en restricciones utilizando la métrica K2 para hacer consultas si un paciente tiene o no astigmatismo de acuerdo a los síntomas presentados en la base de datos de Lentes, también para decidir si una persona vive o muere de acuerdo al conjunto de datos de COVID-19 de la CDMX.

Una red bayesiana es un modelo probabilístico que representa un conjunto de variables y sus dependencias mediante un grafo dirigido. Cada nodo del grafo es una variable, y las flechas (arcos) entre nodos indican relaciones de causalidad o dependencia.
La red utiliza la teoría de probabilidad de Bayes para calcular la probabilidad de que ocurran ciertos eventos, dado que se conocen otros. Es útil para hacer inferencias y tomar decisiones en situaciones de incertidumbre.

El código se puede ejecutar en Google Colab o en Jupyter en local, si este es el caso, se debe primero instalar las bibliotecas de igraph (para saber si un grafo tiene ciclos o no), pgmpy (para acceder a las funciones que crean el modelo de red bayesiana [estructura], a la métrica K2 y al cálculo de las tablas de probabilidad [parámetros de una red bayesiana] de la red).
