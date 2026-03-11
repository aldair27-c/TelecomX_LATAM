# Análisis de Evasión de Clientes (Churn) - Telecom X

## Descripción del proyecto

Este proyecto tiene como objetivo analizar la evasión de clientes (Churn) en una empresa de telecomunicaciones llamada Telecom X. 

A través de técnicas de análisis de datos se busca identificar patrones y factores que influyen en la cancelación del servicio por parte de los clientes.

El análisis incluye procesos de extracción, transformación y limpieza de datos (ETL), así como análisis exploratorio y visualización de información.

---

## Objetivo

Identificar los principales factores asociados a la evasión de clientes para generar insights que ayuden a mejorar las estrategias de retención de la empresa.

---

## Tecnologías utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## Estructura del proyecto

TelecomX_LATAM/

│

├── TelecomX_LATAM.ipynb

└── README.md

---

## Proceso del análisis

El proyecto se desarrolló en las siguientes etapas:

1. **Extracción de datos**
   - Los datos fueron obtenidos desde una API en formato JSON.

2. **Limpieza y tratamiento de datos**
   - Desanidación de estructuras JSON.
   - Identificación de valores faltantes.
   - Corrección de inconsistencias.
   - Creación de nuevas variables como *Cuentas_Diarias*.

3. **Análisis exploratorio de datos**
   - Análisis de la variable churn.
   - Análisis de variables categóricas.
   - Análisis de variables numéricas.
   - Visualización de patrones mediante gráficos.

4. **Conclusiones y recomendaciones**
   - Identificación de factores asociados a la evasión de clientes.

---

## Principales hallazgos

- Los clientes con **contratos mensuales (Month-to-month)** presentan mayor tasa de cancelación.
- Los clientes con **cargos mensuales más altos** tienen mayor probabilidad de churn.
- Los primeros meses de servicio son críticos para la retención de clientes.
- Algunos métodos de pago presentan mayor tasa de cancelación.

---

## Cómo ejecutar el proyecto

1. Clonar el repositorio
