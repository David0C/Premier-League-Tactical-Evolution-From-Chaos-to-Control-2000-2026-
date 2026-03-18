# Premier League Tactical Evolution: From Chaos to Control (2000-2026) ⚽📊

¿Se ha vuelto la Premier League más predecible? Este proyecto utiliza **Data Science** para analizar la transformación táctica de la liga inglesa a lo largo de 26 temporadas, comparando la era del "vértigo individual" contra la actual era del "control sistemático".

## 🎯 Objetivo del Proyecto
El propósito de este análisis es validar o refutar la percepción de los aficionados sobre la "robotización" del fútbol moderno. A través de la extracción de datos de **FBRef** y **WhoScored**, se evalúan métricas de agresión, control de posesión y eficiencia goleadora para identificar patrones de cambio en el ADN de la competición.

## 💡 Hallazgos Clave (Insights)

* **La Muerte del Riesgo:** Los datos confirman una caída sostenida en el volumen de regates y tiros por partido, priorizando la retención de balón y la precisión de pase.
* **El Resurgimiento de la Pizarra:** Los goles a balón parado han alcanzado un pico del **28.8%** en la temporada actual, compensando la dificultad de romper bloques bajos en juego abierto.
* **El Mito de la Experiencia:** Se demostró una correlación casi nula (**-0.190**) entre la edad media de las plantillas y el éxito en la posesión, evidenciando que el control táctico es ahora un proceso metodológico y no solo de veteranía.
* **Identificación de 'Rebeldes':** El análisis de *outliers* destacó casos como el **Leicester City (15-16)**, que logró el éxito con métricas antisistémicas (baja precisión de pase pero alta letalidad).

## 🛠️ Stack Tecnológico
* **Lenguaje:** Python 3.x
* **Librerías:** Pandas (ETL), Matplotlib & Seaborn (Visualización), NumPy (Cálculos Estadísticos).
* **Entorno:** Jupyter Notebook / Cursor.
* **Metodología:** Web Scraping, Data Merging y Análisis Multivariado.

## 📂 Estructura del Repositorio

* `notebooks/`: Contiene el código completo, desde la carga de datos hasta la generación de gráficas.
* `data/`: CSVs procesados de FBRef y WhoScored (Fouls, Goals, Shoots y el Master DF).
* `output/`: Visualizaciones finales del estudio en alta resolución.

## 📊 Descripción de los Datasets
1. **df_premier_final:** El dataset maestro consolidado con todas las variables normalizadas (2000-2026).

---
## 👷‍♂️ Sobre el Autor
**Ingeniero Electrónico** apasionado por el **Sports Analytics**. Mi enfoque combina la precisión de la ingeniería con la curiosidad de los datos deportivos para encontrar ventajas competitivas en el campo de juego. 

📫 **¿Quieres conectar?** [Tu perfil de LinkedIn o Email]
