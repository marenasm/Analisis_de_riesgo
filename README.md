# Análisis de Riesgo Crediticio

Análisis y modelado de riesgo crediticio mediante técnicas de Machine Learning para clasificación binaria de clientes en categorías de riesgo.

## Descripción del Proyecto

Este proyecto implementa un pipeline completo de análisis de riesgo crediticio, desde la exploración y preprocesamiento de datos hasta la evaluación de múltiples modelos de clasificación. El objetivo es identificar patrones en el comportamiento crediticio de los clientes para predecir su nivel de riesgo (Good/Bad).

### Características principales:

- **Análisis Exploratorio de Datos (EDA)**: Visualización de distribuciones, correlaciones y patrones en los datos
- **Preprocesamiento de Datos**: Limpieza, normalización y preparación de features
- **Modelado Predictivo**: Evaluación de múltiples algoritmos de clasificación
- **Evaluación de Modelos**: Métricas de desempeño incluyendo accuracy, precision, recall, ROC-AUC
- **Análisis de Riesgo**: Interpretación de resultados desde una perspectiva de gestión de riesgos

## Stack Tecnológico

- **Python 3.x**
- **pandas**: Manipulación y análisis de datos
- **NumPy**: Operaciones numéricas
- **scikit-learn**: Machine Learning y métricas de evaluación
- **LightGBM**: Gradient Boosting (modelos avanzados)
- **Matplotlib & Seaborn**: Visualización de datos

## Instalación

### Requisitos previos

- Python 3.7 o superior
- pip o conda

### Setup en macOS y Linux

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

O utilizando el script de instalación:

```bash
source setup.sh
```

### Setup en Windows

```bash
python3 -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

O ejecutar:

```bash
setup.bat
```

## Uso

El análisis se encuentra documentado en el Jupyter Notebook principal:

```bash
jupyter notebook notebook.ipynb
```

El notebook incluye:
1. Carga y exploración de datos
2. Análisis estadístico y visualizaciones
3. Preprocesamiento y feature engineering
4. Entrenamiento de modelos (Regresión Logística, Naive Bayes, SVM, LightGBM)
5. Evaluación y comparación de modelos
6. Recomendaciones de riesgo

## Modelos Implementados

- **Regresión Logística**: Modelo base interpretable
- **Naive Bayes**: Clasificador probabilístico
- **Support Vector Machine (SVM)**: Clasificación no-lineal
- **LightGBM**: Gradient Boosting de alto rendimiento

## Métricas de Evaluación

- Accuracy (Precisión Global)
- Precision & Recall
- F1-Score
- ROC-AUC
- Matriz de Confusión
- Classification Report

## Estructura del Proyecto

```
├── notebook.ipynb          # Análisis completo del proyecto
├── data/
│   └── german.csv         # Dataset de crédito alemán
├── requirements.txt        # Dependencias de Python
├── setup.py               # Configuración del paquete
├── setup.sh               # Script de instalación (Linux/macOS)
├── setup.bat              # Script de instalación (Windows)
├── .gitignore             # Archivos ignorados por Git
└── README.md              # Este archivo
```

## Autor

**Mateo Arenas Montoya**
- Ingeniero Físico
- Especialista en Analítica
- Email: mateo0431@gmail.com

## Licencia

Este proyecto es de uso educativo y técnico.
