# Landing Page A/B Experiment Analysis

Este repositorio contiene el análisis detallado de un experimento A/B realizado en una página de aterrizaje (landing page) con versiones **A y B**.

El dataset `landing_experiment.csv` incluye información de usuarios expuestos a estas dos versiones, incluyendo región, dispositivo, fuente de tráfico, tipo de usuario, conversión y gasto. El objetivo es evaluar el rendimiento de cada versión para tomar decisiones de negocio basadas en datos.

📂 **Contenido del repositorio**

`notebooks/landing_experiment_analysis.ipynb` → Notebook principal con carga de datos, validación, pruebas estadísticas (t-test, Chi-cuadrado), visualizaciones y conclusiones.

▶ **Cómo abrir el notebook en Google Colab**
Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/villabon89-commits/Landing_Experiment/blob/main/notebooks/landing_experiment_analysis.ipynb)

O:

1.  Abre el archivo `.ipynb` en GitHub.
2.  Haz clic en `Open in Colab`.

📘 **Cómo reproducir el análisis**

1.  Abre `notebooks/landing_experiment_analysis.ipynb`.
2.  Ejecuta las celdas en orden.
3.  El notebook carga automáticamente el dataset `landing_experiment.csv` (asumiendo que está en el mismo directorio o especificado el path correcto).

🧠 **Objetivo del análisis**

-   Comparar el **gasto promedio** por usuario entre la página A y B.
-   Comparar la **tasa de conversión** entre la página A y B.
-   Revisar la **relación entre la fuente de tráfico y la conversión**.
-   Revisar la **relación entre el tipo de usuario y la conversión**.
-   **Visualizar los resultados** mediante gráficos claros.
-   Recomendar **qué versión de landing page es mejor**, justificando la decisión con datos.
