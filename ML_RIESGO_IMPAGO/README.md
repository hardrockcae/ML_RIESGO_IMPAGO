#  ML_RIESGO_IMPAGO / ML_RISK_PREDICTION

##  Descripción del proyecto | Project Description

**ES 🇪🇸**  
Este proyecto de Machine Learning tiene como objetivo predecir el **riesgo de impago** de clientes en base a variables como precio de compra, plazo mensual, localización, edad, marca del vehículo, género, y días de retraso en el pago. Se construye un modelo supervisado que clasifica a los clientes en distintos niveles de riesgo ("no delay", "early", "medium", "late", "external", "realdebt").

**EN 🇬🇧**  
This Machine Learning project aims to predict the **payment default risk** of customers based on features such as purchase price, monthly payment, location, age, vehicle brand, gender, and days of delay. A supervised model is built to classify customers into different risk buckets ("no delay", "early", "medium", "late", "external", "realdebt").

---

##  Dataset

**ES 🇪🇸**  
El conjunto de datos es de uso privado y ha sido anonimizado. Contiene información de clientes, condiciones de compra y datos contractuales. Se ha incluido una muestra representativa en la carpeta `/src/data_sample/` con un tamaño inferior a 5 MB.

**EN 🇬🇧**  
The dataset is private and anonymized. It contains customer data, purchase conditions, and contract details. A representative sample is included in the `/src/data_sample/` folder, with a size below 5 MB.

---

##  Solución adoptada | Adopted Solution

**ES 🇪🇸**  
1. Limpieza de datos y análisis exploratorio (EDA)  
2. Ingeniería de variables: cálculo de edad, codificación de género, bucket de riesgo a partir de "vencimiento"  
3. Pipeline de modelado con Scikit-learn  
4. Entrenamiento y evaluación de modelos  
5. Guardado del modelo final (`.pkl`) en `/src/models/`  
6. Notebook resumen ejecutable en `/src/results_notebook/`

**EN 🇬🇧**  
1. Data cleaning and exploratory data analysis (EDA)  
2. Feature engineering: age calculation, gender encoding, risk bucketing from "delay days"  
3. Modeling pipeline using Scikit-learn  
4. Model training and evaluation  
5. Final model saved (`.pkl`) in `/src/models/`  
6. Summary executable notebook in `/src/results_notebook/`

---

##  Estructura del repositorio | Repository Structure

```
ML_RIESGO_IMPAGO/
├── README.md                     ← Este archivo / This file
├── src/
│   ├── data_sample/              ← Dataset de muestra / Sample dataset
│   ├── img/                      ← Imágenes utilizadas / Project images
│   ├── models/                   ← Modelos guardados / Trained models
│   ├── notebooks/                ← Notebooks de trabajo / Development notebooks
│   ├── results_notebook/        ← Notebook final del proyecto / Final report notebook
│   └── utils/                    ← Funciones y clases auxiliares / Helper functions
```

---

## 💻 Tecnologías utilizadas | Technologies Used

- Python 3
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

##  Autor | Author

Carlos Escobar  
 Madrid, España  
 [hardrockcae@hotmail.com]
