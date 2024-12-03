# Análisis y Visualización de Datos de Capacidad Asistencial

Este repositorio contiene un conjunto de herramientas para analizar y visualizar datos históricos relacionados con casos de COVID-19 surgidos en España y sus distintas comunidades autónomas. El análisis incluye desde la exploración de datos hasta la creación de visualizaciones básicas y avanzadas. A través de este trabajo, se busca no solo representar gráficamente la información, sino también preparar los datos de manera adecuada para obtener conclusiones más claras y precisas.

El repositorio utiliza **pandas**, **numpy** y **matplotlib** para realizar tareas de procesamiento, análisis y visualización de datos, y sigue un enfoque incremental que facilita el aprendizaje y aplicación de estas herramientas.

## Archivos incluidos

1. **Datos_Capacidad_Asistencial_Historico.csv**  
   Este es el dataset utilizado en los notebooks. Contiene información histórica sobre casos de COVID-19, incluyendo datos sobre la capacidad asistencial en España y sus comunidades autónomas.  

2. **Graph.ipynb**  
   En este archivo se exploran conceptos básicos de visualización de datos con `matplotlib.pyplot`, incluyendo:  
   - Creación de gráficos simples como:
     - Barras apiladas.
     - Barras agrupadas.
     - Series de tiempo.  
   - Personalización de gráficos con funciones como:
     - `markersize`: para ajustar el tamaño de los marcadores en los gráficos.
     - `grid`: para añadir líneas de fondo.
     - Configuración de colores, títulos y etiquetas.
   - Introducción a la manipulación de figuras (`fig`) y ejes (`plt`).
   - Primer acercamiento a la manipulación de ejes (`ax`), para mejorar la organización de gráficos.  

3. **Mod2_Ejm.ipynb**  
   Este archivo amplía el análisis realizado en el primero y lleva las visualizaciones al siguiente nivel:  
   - **Exploración y preparación de datos:**
     - Creación y manipulación de nuevas variables como promedios móviles y otras métricas relevantes.
     - Eliminación de datos atípicos para mejorar la calidad de los análisis.
   - **Gráficos avanzados:**
     - Series de tiempo con suavización mediante media móvil (evitando el "efecto serrucho").
     - Barras y combinaciones de gráficos para representar diferentes aspectos de los datos.  
   - **Automatización de procesos:**
     - Uso de funciones y bucles para automatizar la generación de gráficos.
     - Creación iterativa de figuras con múltiples subgráficos (`12 ax` en una sola figura).  
   - **Análisis dinámico y detallado:** 
     - Los gráficos reflejan los resultados de las transformaciones realizadas sobre los datos, permitiendo una visualización más clara de las tendencias.

## Librerías utilizadas

- **pandas**: Para la manipulación y análisis de datos.
- **numpy**: Para la generación de series numéricas y operaciones matemáticas.
- **matplotlib.pyplot**: Para la creación y personalización de gráficos.

## Instrucciones

1. Descarga el dataset `Datos_Capacidad_Asistencial_Historico.csv`.
2. Abre los notebooks en el orden sugerido:
   - Primero, explora los conceptos básicos en `Graph.ipynb`.
   - Luego, profundiza en visualizaciones avanzadas y análisis detallados en `Mod2_Ejm.ipynb`.
3. Asegúrate de instalar las dependencias necesarias:
   ```bash
   pip install pandas numpy matplotlib
