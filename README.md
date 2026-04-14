# Análisis Exploratorio de Datos: Catálogo de Netflix (1990-2021)

Este proyecto realiza un análisis descriptivo del dataset de Netflix para identificar tendencias de producción, con un enfoque específico en contenido histórico de la década de los 90.

## Objetivo del Proyecto
Trabajar con limpieza de datos, manipulación de DataFrames con Python y visualización de resultados estadísticos de resumen.

## Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Librerías:** * `Pandas`: Limpieza y manipulación de datos.
    * `Matplotlib` & `Seaborn`: Visualización estadística.
    * `Jupyter Notebooks`: Entorno de desarrollo interactivo.

## Análisis Realizado
1. **Limpieza de Datos:** Tratamiento de valores nulos en columnas críticas como `director` y `country`.
2. **Ingeniería de Atributos:** Conversión de la columna `duration` (texto) a valores numéricos para análisis cuantitativo.
3. **Filtrado Avanzado:** Identificación de películas de acción producidas en los años 90 con una duración menor a 90 minutos (optimización de tiempos de visualización).
4. **Visualización:** Generación de gráficos de barras para comparar la proporción de películas frente a series de TV.

## Cómo ejecutarlo
1. Clonar el repositorio.
2. Crear un entorno virtual: `python -m venv venv`.
3. Activar el entorno e instalar dependencias: `pip install -r requirements.txt` (proximamente).
4. Ejecutar el archivo `analisis_netflix.ipynb`.

---
*Proyecto desarrollado como portafolio personal para desarrollo de habilidades con miras a una carrera en DS*