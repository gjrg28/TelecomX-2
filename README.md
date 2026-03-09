# 📊 Telecom Customer Churn Analysis

Este proyecto utiliza técnicas de Machine Learning para predecir la probabilidad de que un cliente cancele su servicio de telecomunicaciones. El análisis se enfoca en identificar los factores clave de abandono para proponer estrategias de retención.

## 🚀 Contenido del Proyecto
- **Limpieza de Datos:** Consolidación de categorías y manejo de valores nulos.
- **Análisis Estadístico:** Prueba de Chi-cuadrado para selección de variables categóricas.
- **Modelado:** Implementación y comparación de:
  - Árboles de Decisión.
  - Regresión Logística.
  - Random Forest Classifier (Modelo Final).
- **Evaluación:** Uso de matrices de confusión, Curvas ROC/AUC y reportes de clasificación (Precision/Recall).

## 📈 Hallazgos Clave
- El **Tipo de Contrato** es el factor más determinante; los contratos mensuales son los de mayor riesgo.
- Los clientes con **menor antigüedad** requieren programas de fidelización inmediata.
- El modelo **Random Forest** superó a los modelos base en la detección de fugas reales (Recall).

## 🛠️ Tecnologías Utilizadas
- Python 3.x
- Pandas & Numpy
- Scikit-learn
- Matplotlib & Seaborn

## 📂 Cómo usar este repositorio
1. Abre el archivo `.ipynb` en Google Colab o Jupyter Notebook.
2. Asegúrate de tener instalado `requirements.txt` (si aplica).
3. Ejecuta las celdas secuencialmente para replicar el entrenamiento y la evaluación.
