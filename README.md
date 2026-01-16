# Detección y tratamiento de dislexia aplicando Machine Learning

Este repositorio contiene el desarrollo completo de mi **Trabajo Fin de Grado (TFG)** en Ingeniería en Tecnologías de Telecomunicación, centrado en la **detección y tratamiento de la dislexia mediante modelos de Machine Learning**, así como el desarrollo de una **aplicación web accesible** que integra dicho modelo.

El objetivo del proyecto es poner a disposición de cualquier usuario una herramienta que permita **detectar indicios de dislexia de forma temprana** y ofrecer **ejercicios de entrenamiento cognitivo** en un entorno dinámico y accesible.

---

## Descripción del proyecto

El proyecto se divide en dos grandes bloques:

1. **Diseño, entrenamiento y evaluación de modelos de Machine Learning** para la detección de dislexia.
2. **Desarrollo de una aplicación web** que integra el modelo y permite al usuario realizar el test y ejercicios de entrenamiento.

El modelo de Machine Learning se basa en un estudio realizado en colegios públicos de España en 2020, con más de **5.000 alumnos de entre 7 y 17 años**, compuesto por un test de **32 preguntas** relacionadas con habilidades de lectura y escritura.

La aplicación web recrea dicho test y proporciona:
- Un test de detección de dislexia.
- Información relevante sobre el trastorno.
- Ejercicios interactivos de entrenamiento cognitivo.
- Un sistema de autenticación y gestión de usuarios.
- Funcionalidades de accesibilidad orientadas a todo tipo de usuarios.

---

## Modelos de Machine Learning

Se han implementado y comparado distintos algoritmos de clasificación supervisada:

- K-Nearest Neighbors (KNN)
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest

Para la evaluación de los modelos se han utilizado métricas como:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**

Tras el análisis comparativo y la gestión de desbalanceo de clases, el modelo final seleccionado es **Support Vector Machine (SVM)**, alcanzando una **exactitud del 96%**.

---

## Aplicación web

La aplicación web ha sido desarrollada utilizando **Django**, aprovechando su integración con Python y su sistema de gestión de usuarios.

Principales características:
- Implementación completa del test de detección de dislexia.
- Ejercicios de entrenamiento diseñados de forma interactiva.
- Sistema de autenticación (registro, inicio de sesión, recuperación de contraseña).
- Diseño accesible, compatible con lectores de pantalla y criterios WCAG.
- Interfaz pensada para una experiencia de usuario clara y sencilla.

---

## Tecnologías utilizadas

- **Python**
- **Scikit-learn**
- **Imbalanced-learn**
- **NumPy**
- **Pandas**
- **Django**
- **SQLite**
- **HTML / CSS**
- **Git & GitHub**

---

## Estructura del proyecto

El repositorio incluye:
- Código del modelo de Machine Learning.
- Código de la aplicación web en Django.
- Scripts de entrenamiento y evaluación del modelo.
- Integración del modelo en la aplicación web.
- Recursos relacionados con accesibilidad y experiencia de usuario.

---

## Estado del proyecto

Este proyecto ha sido desarrollado con fines **académicos** como Trabajo Fin de Grado.  
La solución presentada es **funcional y completa**, aunque no está planteada como un producto final en producción, sino como una **prueba de concepto sólida** que demuestra la viabilidad del uso de Machine Learning en la detección y tratamiento de la dislexia.

---

## Autor

**Blanca María de Pedro Morejón**  
Grado en Ingeniería en Tecnologías de Telecomunicación  
Universidad Pontificia Comillas (ICAI)  
Madrid, 2023
