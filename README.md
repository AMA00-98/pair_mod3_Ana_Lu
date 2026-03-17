# Pair Programming: Módulo 3 - Análisis de Datos con NumPy y Pandas

Este repositorio contiene una serie de ejercicios prácticos desarrollados durante el Módulo 3, enfocados en el dominio de las librerías fundamentales para el análisis de datos en Python: **NumPy** y **Pandas**.

## 🎯 Objetivos del Proyecto

- Comprender la estructura y manipulación de arrays multidimensionales con NumPy.
- Dominar el uso de Series y DataFrames en Pandas para la gestión de conjuntos de datos.
- Practicar técnicas de indexación avanzada (`loc`, `iloc`), filtrado condicional y limpieza de datos.
- Realizar análisis estadísticos básicos sobre datos reales y generados aleatoriamente.

## 🛠️ Tecnologías Utilizadas

- **Lenguaje:** Python 3.x
- **Librerías Principales:**
  - [NumPy](https://numpy.org/): Procesamiento numérico y manejo de arrays.
  - [Pandas](https://pandas.pydata.org/): Estructuras de datos y herramientas de análisis.
- **Entorno:** Jupyter Notebook (.ipynb)

## 📁 Estructura del Repositorio

El proyecto se divide en dos lecciones principales:

### 1. Lección 01: Fundamentos de NumPy
Contenido en `mod3_pair_leccion_01_numpy.ipynb`.
- **Creación de Arrays:** Generación de arrays 1D, 2D y 3D con valores aleatorios y definidos.
- **Indexación y Slicing:** Acceso a elementos específicos y subconjuntos de datos.
- **Estadística:** Uso de funciones como `mean`, `max`, `min` y `round`.
- **Lógica Condicional:** Reemplazo de valores basado en condiciones estadísticas.
- *Nota:* Se incluye un archivo `mod3_pair_leccion_01_numpy.md` con una explicación detallada de estos ejercicios.

### 2. Lección 02: Introducción a Pandas
Contenido en la carpeta `mod3_pair_leccion_02_Pandas/`.
- **DataFrames:** Conversión de arrays a tablas, carga de archivos CSV (`medallas.csv`, `world-data-2023_part1.csv`).
- **Manipulación de Datos:**
  - Selección de filas y columnas mediante etiquetas (`loc`) e índices enteros (`iloc`).
  - Aplicación de filtros booleanos (máscaras) para responder preguntas de negocio.
  - Creación de nuevas columnas calculadas.
- **Series:** Creación a partir de listas y diccionarios, exploración de atributos (`shape`, `size`, `dtype`).

## 🚀 Cómo usar este repositorio

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/pair_mod3_Ana_Lu.git
   ```
2. Asegúrate de tener instaladas las dependencias:
   ```bash
   pip install numpy pandas notebook
   ```
3. Abre los notebooks en tu entorno local:
   ```bash
   jupyter notebook
   ```
