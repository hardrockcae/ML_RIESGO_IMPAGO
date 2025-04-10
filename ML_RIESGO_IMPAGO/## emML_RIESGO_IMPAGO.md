## emML_RIESGO_IMPAGO

 Descripción del Proyecto / Project Description

## ESPAÑOL
El objetivo de este proyecto de Machine Learning es predecir el riesgo de impago de un cliente en base a variables personales y del contrato. Utilizamos un modelo supervisado de clasificación (Random Forest) para categorizar el riesgo en diferentes niveles como: no delay, early, medium, late, external, y realdebt.

ENGLISH
The goal of this Machine Learning project is to predict a customer's default risk based on personal and contract-related features. A supervised classification model (Random Forest) is used to categorize risk into levels such as: no delay, early, medium, late, external, and realdebt.

## Dataset

Nombre: CAR4CASH_DATA.xlsx

Ubicación: C:\Users\hardr\OneDrive\Pictures\Datos adjuntos\Documents\Desktop\Python_scripts\ML_RIESGO_IMPAGO\src\data_sample\CAR4CASH_DATA.xlsx

Columnas principales:

Precio de compra en € / Purchase Price

Plazo mensual / Monthly Term

Vencimiento / Overdue Days

Código postal / ZIP Code

Ciudad / City

Edad / Age

Marca / Brand

Modelo / Model

Partner / Partner

Género / Gender

Columna objetivo / Target column: Bucket (creada a partir de "Vencimiento")

📆 Estructura del repositorio / Repository Structure

ML_RIESGO_IMPAGO/
├── README.md
└── src/
    ├── data_sample/          # Dataset de entrada / Input sample dataset
    ├── img/                  # Gráficas generadas (EDA y modelo) / Generated charts
    ├── models/               # Modelo entrenado .pkl / Trained model
    ├── notebooks/            # Notebooks de trabajo / Work notebooks
    ├── results_notebook/     # Notebook final con el modelo y resultados / Final notebook
    └── utils/                # Código de soporte / Support functions or helpers

### Solución adoptada / Adopted solution

## ESPAÑOL
Se aplicó un pipeline que incluye:

Preprocesamiento de columnas numéricas y categóricas.

Imputación de nulos.

Codificación de variables categóricas.

Entrenamiento con Random Forest.

Evaluación mediante classification report y matriz de confusión.

ENGLISH
The pipeline includes:

Preprocessing of numeric and categorical features.

Missing value imputation.

One-hot encoding for categorical variables.

Training with Random Forest.

Evaluation using classification report and confusion matrix.

## Resultados / Results

El modelo fue entrenado y guardado como modelo_riesgo_impago.pkl

Se realizaron predicciones sobre nuevos datos.

Se evaluó la importancia de las variables.

## Presentación / Presentation

El repositorio incluye:

Imágenes EDA en src/img

Notebook resumen en src/results_notebook

Presentación para el vídeo

Para ejecutar el notebook final, abre el archivo en src/results_notebook y sigue las celdas paso a paso. Puedes reutilizar el modelo con nuevos datos siempre que tengan el mismo formato y columnas que el dataset original.



