# Predicción de precio de diamantes mediante Redes Neuronales

En este proyecto se construye y entrena una red neuronal para un problema de regresión, con el objetivo de predecir el precio de un diamante a partir de sus características. Se realiza un preprocesamiento de los datos, incluyendo su división en conjuntos de entrenamiento, validación y prueba. Posteriormente, el modelo se entrena utilizando técnicas de regularización y callbacks, como Early Stopping y el ajuste dinámico del learning rate. Finalmente, se evalúa el rendimiento mediante métricas de error y el análisis de predicciones frente a valores reales.

**Objetivo:** construir un modelo capaz de predecir el precio de un diamante en función de sus características.

**Tecnología utilizada:**
- Python
- NumPy, Pandas
- TensorFlow / Keras
- Scikit-learn
- Matplotlib

**Resultados:**
- MAE ≈ 330 $
- R² = 0.98 (alta capacidad explicativa del modelo)
- Buen ajuste general, sin evidencias claras de sobreajuste.
