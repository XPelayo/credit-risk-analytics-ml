# Clasificador de Riesgo de Crédito Explicable

Descripción

Este repositorio contiene el código y la documentación para una aplicación analítica basada en Python, diseñada para predecir la probabilidad de incumplimiento (default) en solicitudes de préstamos. A diferencia de las soluciones tradicionales de "caja negra", esta herramienta utiliza modelos de Machine Learning junto con técnicas de interpretabilidad (SHAP) para ofrecer decisiones financieras transparentes, justificando los motivos detrás de la aprobación o denegación de cada crédito.

Objetivos

Desarrollar un modelo predictivo robusto: Entrenar un algoritmo de clasificación (como XGBoost o Random Forest) capaz de identificar patrones de riesgo de alta fiabilidad.

Integrar explicabilidad algorítmica: Utilizar librerías como SHAP para asegurar que cada predicción pueda ser interpretada y justificada ante analistas y reguladores.

Desplegar una interfaz interactiva: Construir un prototipo funcional (utilizando herramientas como Streamlit) que permita a los usuarios introducir datos financieros y obtener un scoring en tiempo real.

Plan de Trabajo Inicial

El proyecto se desarrollará siguiendo las siguientes fases:

Adquisición y Análisis Exploratorio de Datos (EDA): Descarga del dataset (Home Credit Default Risk), análisis de distribuciones, correlaciones e identificación de valores atípicos.

Preprocesamiento y Feature Engineering: Limpieza de datos, imputación de valores nulos, codificación de variables categóricas, escalado y balanceo de clases.

Entrenamiento y Validación de Modelos: Pruebas con diferentes algoritmos de aprendizaje supervisado, ajuste de hiperparámetros y evaluación mediante métricas clave (ROC-AUC, F1-Score).

Integración de Explicabilidad: Implementación del análisis SHAP para interpretar la importancia de las variables a nivel global y local.

Desarrollo de la Interfaz y Despliegue: Creación de la aplicación de usuario, integración con el modelo entrenado y documentación final del proyecto.
