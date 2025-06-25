# 🚖 Análisis de Viajes en Taxi en Chicago + Prueba de Hipótesis
Exploración de datos urbanos y análisis estadístico usando Python

## 📌 Introducción
Este proyecto analiza datos de viajes en taxi en la ciudad de Chicago durante noviembre de 2017. Se divide en dos partes principales:

1. **Análisis Exploratorio** de viajes por compañía y por barrio.
2. **Prueba de Hipótesis** sobre el impacto de la lluvia en la duración de viajes entre el Loop y el aeropuerto O’Hare.

## 🎯 Problema de negocio
Las compañías de taxi y las autoridades de transporte desean comprender los patrones de movilidad urbana, especialmente bajo condiciones climáticas variables. Saber si la lluvia afecta la duración de los viajes podría mejorar la planificación y los recursos.

## 🔍 Objetivos del proyecto
✔ Analizar viajes por empresa y ubicación de destino  
✔ Visualizar la distribución y patrones de viajes  
✔ Identificar los barrios más frecuentados  
✔ Evaluar el impacto del clima en la duración de viajes  
✔ Formular y probar hipótesis estadísticas  

## ❓ Preguntas clave
- ¿Qué empresas realizaron más viajes el 15 y 16 de noviembre?  
- ¿Cuáles son los barrios con más finalizaciones de trayectos?  
- ¿La duración de los viajes cambia los sábados lluviosos?

## 📊 Métricas clave
📌 Análisis exploratorio:
- Número de viajes por empresa  
- Promedio de viajes por barrio  
- Visualizaciones de frecuencia  

📌 Prueba de hipótesis:
- Promedio de duración de viajes con y sin lluvia  
- T-statistic y p-value  
- Nivel de significancia (α) y decisión  

## 🗂 Descripción del conjunto de datos
📁 `/datasets/project_sql_result_01.csv`: viajes por empresa (15-16 nov)  
📁 `/datasets/project_sql_result_04.csv`: viajes por barrio (noviembre)  
📁 `/datasets/project_sql_result_07.csv`: duración de viajes Loop → Aeropuerto

Columnas clave:
- `company_name`, `trips_amount`, `dropoff_location_name`, `average_trips`  
- `start_ts`, `weather_conditions`, `duration_seconds`

## ⚙️ Proceso de análisis
📌 Herramientas: Python, Pandas, Matplotlib, Seaborn, SciPy

### Paso 1: Revisión y limpieza de datos
✔ Tipos de datos  
✔ Valores nulos o atípicos

### Paso 2: Visualización y exploración
✔ Gráficos de barras y comparaciones  
✔ Top 10 barrios y compañías

### Paso 3: Prueba estadística
✔ Hipótesis: ¿la lluvia modifica la duración?  
✔ Aplicación de prueba t para muestras independientes

## 📁 Estructura del repositorio
📂 data  
 └── project_sql_result_01.csv  
 └── project_sql_result_04.csv  
 └── project_sql_result_07.csv  

📂 notebooks  
 └── Proyecto_Sprint8_FINAL.ipynb  

📂 insights  
 └── resumen.md  

## 📬 Contacto
📧 Correo: jessica.elizondo.t@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/jessica-elizondo-t
