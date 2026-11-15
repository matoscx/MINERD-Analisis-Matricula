# 📈 Análisis y Modelado de la Matrícula Escolar en República Dominicana (2015-2024)

> *Proyecto de análisis de datos y machine learning enfocado en las estadísticas oficiales del Ministerio de Educación (MINERD) para estudiar la evolución de la matrícula estudiantil por nivel educativo, regional y distrito.*

Este repositorio contiene un estudio detallado sobre cómo se han distribuido los estudiantes en los niveles Inicial, Primario, Secundario y de Adultos a lo largo de casi una década, utilizando un conjunto de datos abiertos con más de 1,200 registros provenientes del portal oficial del país.

---

## 💡 ¿Qué hicimos en este proyecto?

* **Ingeniería de Datos:** Limpieza, estandarización de nombres de distritos y corrección de inconsistencias temporales en los registros oficiales.
* **Preprocesamiento Avanzado:** Implementación de codificación de variables categóricas (*Label Encoding*) y normalización de datos numéricos para preparar el dataset de cara a algoritmos de Machine Learning.
* **Análisis Exploratorio (EDA):** Creación de visualizaciones dinámicas para comparar el crecimiento de la matrícula entre distintos niveles educativos y detectar disparidades regionales significativas.
* **Preparación para Modelado:** Estructuración de los datos enfocada en variables críticas (como el año de inicio y el ID regional) para facilitar tareas de regresión y series de tiempo.

---

## 💻 Stack Tecnológico

* **Lenguaje:** Python
* **Procesamiento y Limpieza:** Pandas y NumPy
* **Visualización Estadística:** Matplotlib y Seaborn
* **Preprocesamiento:** Scikit-learn (escalamiento y codificación de características)

---

## 📂 Fuente de Datos y Estructura

* **Fuente:** Repositorio de Datos Abiertos de la República Dominicana (*datos.gob.do*), específicamente el dataset de estudiantes matriculados por nivel según regional y distrito.
* **`Modelado_de_Datos_con_Aprendizaje_Automático.ipynb`**: El Jupyter Notebook principal que contiene todo el flujo de análisis, preprocesamiento y experimentación con modelos.

---
*Desarrollado para aplicar la ciencia de datos en la comprensión y evaluación del impacto de las políticas públicas educativas.* ✨
