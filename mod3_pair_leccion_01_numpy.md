# Resumen de Contenido: mod3_pair_leccion_01_numpy.ipynb

Este notebook contiene ejercicios prácticos para el aprendizaje de la librería **NumPy** en Python, enfocándose en la creación de arrays, indexación y el uso de funciones estadísticas.

## 1. Creación e Indexación de Arrays

En esta sección se exploran diferentes métodos para generar arrays y acceder a sus elementos:

- **Ejercicio 1: Array 1D Aleatorio**
  - Creación de un array unidimensional con 50 valores aleatorios entre 10 y 99.
  - Uso de *slicing* para acceder a elementos en posiciones múltiplos de 5 (`[::5]`).
- **Ejercicio 2: Indexación de Posiciones Impares**
  - Creación de un array 1D con 30 valores entre 1 y 20.
  - Acceso a elementos en posiciones impares mediante indexación.
- **Ejercicio 3: Arrays 2D y Redondeo**
  - Generación de una matriz de (4, 6) con números decimales aleatorios.
  - Acceso a la última fila de la matriz.
  - Aplicación de la función `np.round()` para limitar a 2 decimales.

## 2. Funciones Aritméticas y Estadísticas

Se profundiza en el análisis de datos y la manipulación condicional de arrays:

- **Ejercicio 1: Array 3D**
  - Creación de un array tridimensional de forma (2, 3, 5) con valores entre 0 y 1, redondeados a un decimal.
- **Ejercicio 2 y 3: Manipulación Condicional y Estadísticos**
  - Cálculo de métricas estadísticas básicas: media (`np.mean`), máximo (`np.max`) y mínimo (`np.min`).
  - Creación de un array vacío con `np.empty` para almacenar etiquetas de texto.
  - **Lógica de Reemplazo:** Se categorizan los valores del array original basándose en su relación con la media y los valores extremos:
    - `A`: Si el valor es igual a la media.
    - `B`: Si el valor es mayor que la media.
    - `C`: Si el valor es menor que la media.
    - `D`: Si el valor es el máximo.
    - `E`: Si el valor es el mínimo.
