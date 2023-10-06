# 🖥️ Práctico 2 - Analisis multicriterio

Este práctico tiene varias alternativas para ser realizado:

1. Se puede realizar un MCDA completo con una base de datos.
2. Puede implementarse una función de agregación o de calculo de pesos.
3. Buscar el criterio crítico en el dataset de ejemplo.


## 1. MCDA completo con una base de datos

> Utilizando la bases de datos [WorldCupData(1930-2018)](https://www.kaggle.com/datasets/mozattt/worldcupdata19302018)

> Ordenar los partidos según: **cual fue la mejor copa del mundo disputada hasta la fecha**.

> Para eso tienen que tener en cuenta el fairplay, cantidad de puntos, cantidad de goles, importancia del partido, clima en las ciudades, asistencia por partido, asistencia total etc.


Se pide definir almenos 20 criterios que resuman las características a buscar antes mencionadas y reproducir el proceso de MCDA:

1. Identificar y definir las **alternativas** de decisión, que deben ser factibles, exhaustivas y excluyentes. 
2. Definir los **atributos a optimizar**. Identificar objetivos que son de maximización o de minimización.
3. Asociar a cada objetivo o atributo, una **función de utilidad** que permita expresar una valoración cuantitativa de cada alternativa respecto al atributo ($atributo + función = criterio$). 
4. Consignar las valoraciones de cada alternativa respecto de cada criterio en una matriz de decisión.
5. Fija “umbrales de satisfacción” para cada criterio, de manera tal que se eliminen las alternativas que en algún criterio no los superan y Preánalisis de dominancia. 
6. Si se requiere, transformar las valoraciones de las alternativas correspondientes a criterios de maximización.
7. Ponderar o asignar valoraciones a los criterios, conforme a la importancia relativa que tienen para el decisor, mediante una función de utilidad. Consignar en la matriz de decisión los $U(C_j)= w_jv$
8. Escalar/Normalizar todas las valoraciones, consignadas en la matriz de decisión completa, para llevarlas a una escala común y hacerlas comparables. Obtener así la matriz de decisión definitiva.
9. Seleccionar varios **MÉTODO DE AGREGACIÓN**.
10. Hacer un análisis as post-mortem que involucre comparaciones directas y rank-reversals 1.



## 2. Implementar

- Si quieren implementar un método, se sugiere contactarse con el docente y discutir cual método implementar.

Hay dos templates a rellenar depende el caso:

Buscar donde dice: `# YOUR CODE GOES HERE`
 
- [Template para funciones de agregación](./tp2_tpl/tpl_agg.ipynb)

  > Algunas ideas de agregación: Promethee, RIM, y  ~VIKOR~ (Tomado)... pregunten.

- [Template para transformadores de pesos](./tp2_tpl/tpl_weight.ipynb)

    > Algunas ideas de transformadores para calcular pesos: CILOS, MEREC, IDOCRIW, GINI.
    
## 3. Buscar criterio crítico

Si vas a hacer esto, pregunta y mas vale que sepas optimización así  que preguntme


