# Proyecto IA: Predicción de Empleabilidad Estudiantil

## 1. Justificación del Problema y Diagnóstico
* **¿Por qué este problema?:** (Explica el contexto de la inserción laboral estudiantil/egresados y el impacto de la falta de empleabilidad).
* **¿Cómo demostró que existe?:** (Cita estadísticas internas de la institución, informes educativos o métricas del dataset que muestran altas tasas de desempleo/subempleo).
* **¿Por qué es importante resolverlo?:** (Indica el impacto económico/social para los estudiantes y la mejora en los indicadores institucionales).

## 2. Marco Teórico y Justificación Técnica
* **¿Qué dice la literatura?:** (Menciona antecedentes académicos o modelos previos de análisis de inserción laboral o rendimiento estudiantil).
* **¿Por qué utilizar IA?:** (Explica la ventaja de capturar patrones complejos e interacciones no lineales entre múltiples variables frente a métodos estadísticos tradicionales).

## 3. Datos y Variables
* **¿Por qué seleccionó esos datos?:** (Describe la fuente de `dataset_empleabilidad_estudiantil.csv`, representatividad y tamaño muestral).
* **¿Por qué seleccionó esas variables?:** (Detalla las características seleccionadas, p. ej., promedio ponderado, experiencia previa, idioma, certitificaciones, y su fundamentación teórica o técnica).
* **¿Cómo sabe que no existe data leakage?:** (Explica cómo aseguraste que las variables predictores se midieron estrictamente *antes* del evento de contratación/empleabilidad y cómo realizaste la separación train/test antes de cualquier imputación o escalado).

## 4. Diseño Experimental y Modelamiento
* **¿Por qué utilizó ese algoritmo?:** (Justifica el uso de *Logistic Regression* [`logistic_regression.pkl`]: interpretabilidad de los coeficientes, modelo base sólido para clasificación binaria, bajo riesgo de overfitting, etc.).
* **¿Cómo diseñó el experimento?:** (Indica la división del dataset [ej. 80/20 o Stratified K-Fold], técnicas de escalado/imputación aplicadas en `data/processed/` y manejo de desbalance de clases).

## 5. Evaluación, Comparación e Impacto
* **¿Cómo sabe que el modelo funciona?:** (Menciona las métricas de evaluación utilizadas: Accuracy, Precision, Recall, F1-Score, ROC-AUC).
* **¿Contra qué comparó el modelo?:** (Compara la Regresión Logística contra un baseline ingenuo/dummy o contra otros clasificadores como Random Forest o Árboles de Decisión).
* **¿Qué evidencia respalda sus conclusiones?:** (Presenta la matriz de confusión, curvas ROC y tablas comparativas de resultados).
* **¿Qué aporta realmente su investigación?:** (Explica la aplicabilidad práctica: herramienta de alerta temprana para la universidad, identificación de factores clave para mejorar el perfil estudiantil, etc.).