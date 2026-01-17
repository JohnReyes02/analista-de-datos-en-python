# Analista de Datos en Python

Este repositorio contiene el material del programa "Analista de Datos en Python". El objetivo es desarrollar habilidades para manipular, analizar y visualizar datos utilizando Python, sin necesidad de experiencia previa en programación.

## Contenido del Curso

El programa está estructurado en las siguientes secciones:

1.  **Introducción a Python**: Conceptos básicos, listas, funciones, paquetes y NumPy.
2.  **Python Intermedio**: Matplotlib, diccionarios, Pandas, lógica de control y bucles.
3.  **Manipulación de Datos con Pandas**: Transformación, agregación, segmentación y visualización de DataFrames.
4.  **Unir Datos con Pandas**: Fusión de tablas, concatenación y datos ordenados.
5.  **Introducción a la Estadística en Python**: Síntesis estadística, probabilidad, distribuciones y correlación.
6.  **Introducción a la Visualización de Datos con Seaborn**: Gráficos de variables cuantitativas y categóricas.
7.  **Análisis Exploratorio de Datos (EDA)**: Limpieza, imputación y relaciones en los datos.
8.  **Muestreo en Python**: Métodos de muestreo y distribuciones.
9.  **Pruebas de Hipótesis en Python**: Fundamentos, pruebas t, ANOVA y proporciones.

## Tecnologías

*   **Lenguaje**: Python
*   **Librerías Principales**: Pandas, NumPy, Matplotlib, Seaborn, Scipy.
*   **Formato**: Quarto (`.qmd`) y Jupyter Notebooks.

## Configuración del Entorno

Para asegurar la reproducibilidad del proyecto, se recomienda usar un entorno virtual:

1.  **Crear el entorno virtual**:
    ```bash
    python3 -m venv .venv
    ```
2.  **Activar el entorno**:
    *   macOS/Linux: `source .venv/bin/activate`
    *   Windows: `.venv\Scripts\activate`
3.  **Instalar dependencias**:
    ```bash
    pip install -r requirements.txt
    ```

## Cómo Utilizar

Este proyecto está configurado con **Quarto**. Para generar el sitio web localmente:

1.  Instala las dependencias:
    ```bash
    pip install -r requirements.txt
    ```
2.  Renderiza el proyecto:
    ```bash
    quarto preview
    ```
