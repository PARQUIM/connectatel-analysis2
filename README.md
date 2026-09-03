# ConnectaTel – Análisis de Comportamiento de Clientes

Este repositorio contiene el análisis de comportamiento de clientes de ConnectaTel, una empresa de telecomunicaciones con operaciones en México y Colombia, realizado como proyecto final del Sprint 7 (bootcamp de análisis de datos, TripleTen).

El análisis integra tres fuentes de datos (planes, usuarios y uso real del servicio) para construir un perfil de comportamiento por cliente, detectar problemas de calidad de datos, identificar outliers y segmentar la base de clientes según edad y nivel de uso.

## 📂 Contenido del repositorio

- `notebooks/connectatel_analysis.ipynb`
  → Notebook principal con:
  - Carga y exploración de los tres datasets
  - Diagnóstico de calidad de datos (nulos, sentinels, fechas fuera de rango)
  - Limpieza y verificación de missingness (MAR)
  - Construcción de perfil de usuario (agregación de uso por cliente)
  - Estadísticas descriptivas y visualizaciones (histogramas, boxplots)
  - Detección de outliers con IQR
  - Segmentación de clientes por edad y nivel de uso
  - Análisis ejecutivo con recomendaciones comerciales

## 📊 Datasets utilizados

- `plans.csv`: catálogo de planes (precio, minutos, GB, mensajes incluidos, costos por extra)
- `users_latam.csv`: información de clientes (edad, ciudad, fecha de registro, plan, churn)
- `usage.csv`: detalle de uso real (llamadas y mensajes)

## ▶ Cómo abrir el notebook en Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](URL_DEL_NOTEBOOK_EN_GITHUB)

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/connectatel_analysis.ipynb`
2. Ejecuta las celdas en orden, de arriba hacia abajo
3. El notebook carga los tres datasets al inicio

## 🧠 Objetivo del análisis

- Identificar problemas de calidad en los datos de usuarios y uso
- Construir un perfil estadístico del comportamiento de cada cliente
- Detectar outliers y patrones de uso atípico
- Segmentar clientes por edad y nivel de uso
- Generar recomendaciones comerciales para optimizar la oferta de planes
