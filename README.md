# Talent-Flow-Python-Analysis
# 👥 Project Talent Flow: Análisis de Rotación Laboral (People Analytics)

Este proyecto de **People Analytics** utiliza Python para analizar los factores que influyen en la rotación de personal (*attrition*) dentro de una organización. El objetivo es identificar patrones de comportamiento y proponer estrategias basadas en datos para retener el talento clave.

## 🎯 Contexto del Problema
La rotación laboral impacta directamente en la productividad y los costos operativos. Este análisis busca responder:
* ¿Qué factores demográficos (edad, distancia al trabajo) influyen más en la renuncia?
* ¿Existe relación entre la satisfacción laboral y la tasa de salida?
* ¿Qué departamentos presentan mayor riesgo de fuga de talento?

## 🛠 Tecnologías Utilizadas
* **Lenguaje:** Python 🐍
* **Librerías de Análisis:** Pandas, NumPy.
* **Librerías de Visualización:** Matplotlib, Seaborn.
* **Herramientas:** Jupyter Notebook.

## 📊 Análisis y Hallazgos Clave
A través de un Análisis Exploratorio de Datos (EDA) exhaustivo, detectamos los siguientes patrones:
* **Antigüedad Crítica:** Se observó un pico de renuncias en empleados con menos de 1 año y entre 1-3 años de antigüedad.
* **Factor Edad:** La rotación se concentra significativamente en el talento joven.
* **Estancamiento:** La falta de promociones recientes y planes de carrera claros es un detonante fuerte para la salida.
* **Bienestar:** Factores como la distancia al trabajo y el equilibrio vida-trabajo mostraron correlación con la decisión de renunciar.

## 💡 Recomendaciones de Negocio
Basado en los datos, se proponen las siguientes acciones (detalladas en el informe PDF):
1. **Programas de Onboarding:** Reforzar el acompañamiento durante el primer año crítico.
2. **Planes de Carrera:** Visibilizar oportunidades de crecimiento para evitar la percepción de estancamiento.
3. **Bienestar Emocional:** Implementar iniciativas para gestionar el estrés y mejorar el clima organizacional.
4. **Monitoreo Continuo:** Uso de dashboards para identificar empleados en riesgo temprano.

## 📂 Estructura del Dataset
El dataset `PFDA_People_analytics.csv` contiene 35 variables, incluyendo:
* `Attrition`: Variable objetivo (Yes/No).
* `Age`, `Gender`, `MaritalStatus`: Datos demográficos.
* `JobRole`, `Department`, `MonthlyIncome`: Datos laborales.
* `JobSatisfaction`, `EnvironmentSatisfaction`: Métricas de clima.

## 👥 Autores y Créditos (Grupo 4)
Este proyecto fue desarrollado como parte del **Data Foundations Program**.
* José Morales
* Dario Escobar
* Raúl Murillo
* Hermes Quimí
* Carla Reyes

