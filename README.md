# ✈️ Pipeline ETL: Minería de Datos Financieros con Wikipedia API

Proyecto de *Data Mining* e Inteligencia de Mercado orientado a la recopilación y estructuración automatizada de información pública de la industria aerocomercial.

Este sistema utiliza la API de Wikipedia para obtener información de diferentes aerolíneas, procesa el contenido mediante Expresiones Regulares (Regex) y almacena las métricas encontradas en una base de datos SQLite.

**Objetivo del Proyecto:** Transformar grandes volúmenes de información no estructurada en un dataset organizado y reutilizable para análisis financiero, comparación de competidores (benchmarking) y elaboración de dashboards.

## ⚙️ Arquitectura y Flujo de Trabajo

* **1. Extracción Automática:** Se conecta a la API de Wikipedia para descargar la historia de las aerolíneas competidoras.
* **2. Limpieza de Datos (Regex):** Analiza el texto desordenado y busca patrones específicos asociados a dinero o métricas operativas (pasajeros, ingresos, flota).
* **3. Análisis Relacional (SQL):** Carga la información extraída en una base de datos relacional (`SQLite`) para ejecutar consultas que contabilizan qué aerolínea tiene mayor exposición de datos públicos.
* **4. Exportación a Excel:** Genera un dataset estructurado (archivos `.xlsx` y `.csv`) listo para ser consumido en Dashboards de Inteligencia de Mercado.

## 🛠️ Stack Tecnológico

* **Python (Pandas):** Para la limpieza, transformación y manipulación de datos.
* **SQL (SQLite):** Para el almacenamiento temporal y consultas relacionales.
* **Wikipedia-API:** Para la conexión y consumo de fuentes externas.
* **Expresiones Regulares (re):** Para la minería de texto avanzada.
* **Matplotlib:** Para la generación automática de visualizaciones de datos.

## 📂 Archivos del Repositorio

* `*.ipynb`: Cuaderno de código fuente ejecutable.
* `dataset_estructurado_wikipedia.xlsx` y `.csv`: Datasets resultantes limpios y estructurados.
* `analisis_competitivo_wikipedia.png`: Visualización generada automáticamente por el script.
