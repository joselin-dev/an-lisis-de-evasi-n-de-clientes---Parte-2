📊 TelecomX LATAM - Análisis de Churn de Clientes

📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar los factores que influyen en la fuga de clientes (Churn) en una empresa de telecomunicaciones en LATAM.

A través de técnicas de análisis de datos y visualización en Python, se busca identificar patrones que expliquen por qué los clientes cancelan sus servicios.

El análisis incluye extracción de datos, limpieza, preprocesamiento y análisis exploratorio (EDA) para entender mejor el comportamiento de los clientes.

🗂️ Estructura del Proyecto
📁 TelecomX-Churn
│
├── TelecomX2-LATAM.ipynb   # Notebook principal con todo el análisis
├── TelecomX_Data.json      # Dataset utilizado
└── README.md               # Documentación del proyecto

🛠️ Tecnologías Utilizadas

- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

- Plotly

⚙️ Proceso de Análisis

1️⃣ Extracción de Datos

2️⃣ Preprocesamiento

En esta etapa se realizaron tareas como:

- Limpieza de valores faltantes

- Transformación de variables

- Normalización de columnas

- Eliminación de columnas redundantes

- Conversión de tipos de datos

3️⃣ Análisis Exploratorio de Datos (EDA)

Se analizaron distintas variables para identificar patrones asociados con el Churn, utilizando:

- Distribuciones de variables

- Comparación entre clientes que abandonan y los que permanecen

- Visualizaciones para detectar relaciones entre variables

📈 Principales Hallazgos

Los factores que más influyen en la pérdida de clientes son:

- Antigüedad del cliente (Tenure)
Los clientes con menor tiempo en la empresa tienen mayor probabilidad de cancelar el servicio.

- Costo mensual del servicio
A mayor precio mensual, mayor probabilidad de churn.

También se identificó que:

Existe redundancia entre el valor mensual y el cargo diario, por lo que una de estas variables puede eliminarse para simplificar el dataset.

Variables como género y tener servicio telefónico no aportan capacidad predictiva relevante para el churn.

🎯 Objetivo del Proyecto

El objetivo es identificar los factores que contribuyen a la fuga de clientes para que la empresa pueda desarrollar estrategias de retención más efectivas.

💡 Este proyecto forma parte de mi aprendizaje en análisis de datos y ciencia de datos utilizando Python.
