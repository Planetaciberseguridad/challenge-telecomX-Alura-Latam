# challenge-telecomX-Alura-Latam

Proyecto Telecom X – Análisis de Evasión de Clientes

Descripción
Este proyecto analiza datos de clientes de Telecom X con el objetivo de identificar factores que influyen en la cancelación del servicio (churn). Forma parte del programa de especialización en Ciencia de Datos de Alura + ONE.

 Objetivo
Explorar los datos, identificar patrones de evasíon y generar recomendaciones estratégicas basadas en análisis descriptivo y visualizaciones. El análisis servirá como base para modelos predictivos futuros.

 Tecnologías utilizadas
Python 3.10+
Pandas, NumPy
Matplotlib, Seaborn, Plotly
Google Colab

 Estructura del proyecto
TelecomX_LATAM.ipynb: Notebook con el análisis completo, visualizaciones y reporte final.

Informe_Final_TelecomX.md: Documento con el Informe final

imagenes_word: carpeta con imagenes del informe final importante que se descargue junto al md

README.md: Este archivo de referencia del proyecto.

TelecomX_diccionario.md : Diccionario del proyecto

TelecomX_Data.json : Archivo con los datos, en el proyecto se usa url del archivo

Analisis_graficas.word : Analisis que se realizo detallado a cada gráfica

Análisis realizado
Distribución general de cancelación
Análisis por variables personales (edad, pareja, dependientes)
Impacto del tipo de contrato, método de pago y tipo de servicio
Evaluación de variables numéricas (meses, cargos, cuenta diaria)
Correlación entre variables y su relación con la evasíon

 Principales hallazgos
Clientes jóvenes, sin pareja ni dependientes, y con factura electrónica tienen mayor propensión a cancelar.
Contratos mensuales y el método de pago "Electronic Check" están altamente correlacionados con el churn.
Clientes que cancelan suelen hacerlo en los primeros meses del contrato.

 Cómo ejecutar el proyecto
Abre el archivo TelecomX_LATAM.ipynb en Google Colab.
Asegúrate de tener las bibliotecas necesarias (pandas, matplotlib, seaborn, plotly).
Ejecuta todas las celdas desde la importación hasta la generación de visualizaciones y conclusiones.

 Requisitos
Python 3.10+
Bibliotecas instaladas (o usarlas en entorno Colab)
Datos en formato .csv o cargados desde la API proporcionada por el reto
