# 🧠 Human Activity Recognition (HAR) con KNN y SVM

Proyecto desarrollado para reconocer actividades humanas a partir de señales multivariadas (acelerómetro y giroscopio), utilizando la extracción de características con `tsfresh` y modelos implementados manualmente: KNN y SVM multiclase.

---


## 📂 Estructura del proyecto

```bash
Proyecto1_HAR/
├── train.h5
├── test.h5
├── trainfilt/
├── testfilt/
├── HAR_KNN_SVM.ipynb
├── predictions_knn.csv
├── predictions_SVM.csv
└── README.md
---

## 🛠️ Tecnologías utilizadas

- Python 3.x
- Pandas, NumPy, Matplotlib, Seaborn
- tsfresh
- Scikit-learn

---

## 🔄 Flujo del modelo

1. Carga y visualización de señales
2. Preprocesamiento con `tsfresh`
3. Entrenamiento con:
   - KNN implementado manualmente
   - SVM multiclase desde cero
4. Evaluación con accuracy, F1 score y matriz de confusión
5. Exportación de predicciones en `.csv`

---

## 📊 Resultados

- **KNN (k=3)**: ~95.6% accuracy
- **SVM manual**: ~97.8% accuracy
- Coincidencia entre modelos: ~98%

---

## 📎 Créditos

Proyecto realizado como parte del curso *Machine Learning - UTEC*.
