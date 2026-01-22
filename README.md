# Telecom Analysis – Final Project Sprint 7

Este repositorio contiene el análisis realizado durante el Sprint 7 del caso Conectatel.

El dataset `plans` incluye los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).

El dataset `users_latam` incluye información de clientes tales como edad, ciudad, fecha de registro y plan contratado.

El dataset `usage` incluye  el detalle de uso real entre estos las llamadas (duración) y mensajes (longitud).

## 📂 Contenido del repositorio

- `notebooks/S7 Version-Estudiante-Project-ConnectaTel.ipynb`
  → Notebook principal con limpieza, visualizacion, segmentacion, distribuciones, outliers e Insight ejecutivo.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/drive/1Q1IYqHwiODTK8UjAFZ6beAKTUT4qkFUy))](URL_DEL_NOTEBOOK_EN_GITHUB)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `S7 Version-Estudiante-Project-ConnectaTel.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Objetivo del análisis

- Identificar problemas de calidad de datos
- Construir un pipeline de limpieza reproducible
- Analizar comportamientos, distribuciones y outliers
- Detectar outliers y comportamientos atípicos mediante métodos estadísticos y visuales.
- Visualizar diferencias entre segmentos y extraer insights comerciales relevantes.
- Generar insights para el equipo de Estrategia e Integración de Conectatel.
- Construir un perfil estadístico del uso (llamadas y mensajes) por cliente y por segmentos demográficos.
