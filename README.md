# EverPeak Retail Analysis – Sprint 6

Este repositorio contiene el análisis realizado durante el Sprint 7 del caso ConnectaTel.
El objetivo del estudio es identificar patrones de uso, detectar comportamientos atípicos y comprender qué segmentos de clientes muestran necesidades diferenciadas, con el fin de optimizar la oferta comercial y mejorar la experiencia del usuario.

El dataset `plans.csv` contiene los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
`users_latam.csv` contiene información de clientes: edad, ciudad, fecha de registro, plan contratado.
`usage.csv` contiene el detalle de uso real: llamadas (duración) y mensajes (longitud). Con valores faltantes, sentinels, outliers y problemas de calidad diseñados para simular datos reales del retail. :contentReference[oaicite:2]{index=2}

## 📂 Contenido del repositorio

- `S7_Version_Estudiante_Proyect_ConnectaTel.ipynb`
  → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/drive/15pVrVM2l0pgooKrp-87gBy-h2CRAuZIr)](https://github.com/aliciasarazua74-a11y/analisis-connectatel/blob/main/S7_Version_Estudiante_Project_ConnectaTel.ipynb)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `S7_Version_Estudiante_Proyect_ConnectaTel.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Objetivo del análisis

- Integrar y limpiar bases de datos provenientes de tres fuentes distintas.
- Aplicar técnicas de validación, estandarización de tipos de datos y detección de valores inconsistentes.
- Construir un perfil estadístico del uso (llamadas y mensajes) por cliente y por segmentos demográficos.
- Detectar outliers y comportamientos atípicos mediante métodos estadísticos y visuales.
- Crear segmentaciones de clientes basadas en edad y comportamiento de uso.
- Visualizar diferencias entre segmentos y extraer insights comerciales relevantes.
- Documentar todo el proceso en un Jupyter Notebook, junto con un README reproducible para subirlo a GitHub.
