# telecom-churn-analisis1
Análisis de evasión de clientes (Churn) en Telecom X usando Python. Incluye ETL, limpieza de datos, EDA y visualizaciones para identificar patrones de abandono.

# 🚀 Análisis de Churn en Telecomunicaciones

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tallonson69/telecom-churn-analisis1/blob/main/desafio2.ipynb)

## 📋 Descripción
Análisis completo de evasión de clientes (Churn) para compañía de telecomunicaciones, realizado en Google Colab. Proyecto incluye:

- Extracción de datos desde API JSON
- Proceso ETL con Pandas
- Análisis exploratorio (EDA)
- Visualizaciones con Matplotlib
- Recomendaciones estratégicas

## 🔍 Datos Analizados
- **Variables clave**: 
  - `tenure` (antigüedad)
  - `MonthlyCharges` (cargos mensuales)
  - `Contract` (tipo de contrato)
  - `PaymentMethod` (método de pago)

Hallazgos Principales
    72% del Churn ocurre en primeros 18 meses
    Contratos mensuales tienen 3x más abandono que anuales
    68% de clientes con cargos >$80 abandonan
    
Estructura del Proyecto
telecom-churn-analisis1/
├── desafio2.ipynb          # Notebook principal
├── data/
│   ├── raw/               # Datos crudos
│   └── processed/         # Datos limpios
└── README.md
