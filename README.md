## ✈️ Minería de Datos Financieros con Wikipedia API

## 📌 ¿Para qué sirve este proyecto?
Este script automatiza la recopilación de datos de la industria aerocomercial. En lugar de leer manualmente decenas de artículos de Wikipedia para buscar métricas financieras de la competencia, este programa descarga el texto completo, lo limpia y extrae automáticamente cifras clave (como ingresos, inversiones, tamaño de flota y volumen de pasajeros).

## ⚙️ ¿Cómo funciona?
Extracción Automática: Se conecta a la API de Wikipedia para descargar la historia de aerolíneas competidoras.

Limpieza de Datos (Regex): Analiza el texto desordenado y busca patrones específicos asociados a dinero o métricas operativas.

Análisis SQL: Carga la información extraída en una base de datos relacional (SQLite) para contabilizar qué aerolínea tiene mayor exposición de datos públicos.

Exportación a Excel: Genera un dataset estructurado listo para ser consumido en Dashboards de Inteligencia de Mercado.

 ## 🛠️ Stack Tecnológico
Python (Pandas): Manipulación de datos.

SQL (SQLite): Consultas relacionales.

Wikipedia-API: Conexión a fuentes externas.

Matplotlib: Visualización de datos.
