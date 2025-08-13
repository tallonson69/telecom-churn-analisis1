# telecom-churn-analisis1
Análisis de evasión de clientes (Churn) en Telecom X usando Python. Incluye ETL, limpieza de datos, EDA y visualizaciones para identificar patrones de abandono.


Análisis de evasión de clientes (Churn) en el sector telecomunicaciones usando Python y Google Colab

 Descripción

Este proyecto analiza los patrones de abandono de clientes (Churn) en una empresa de telecomunicaciones mediante:
✅ ETL (Extracción, Transformación y Carga) desde una API JSON
✅ Limpieza de datos (manejo de valores nulos, estandarización)
✅ Análisis Exploratorio (EDA) con visualizaciones en Matplotlib
✅ Identificación de factores clave que influyen en la evasión

Objetivo: Reducir la tasa de Churn mediante insights accionables.
 Cómo Usar

    Abrir el Notebook en Colab: Haz clic en el botón https://colab.research.google.com/assets/colab-badge.svg.

    Ejecutar paso a paso: El notebook está listo para correr en Google Colab sin configuraciones adicionales.

    Explorar los datos: Modifica el código según tus necesidades.

 Estructura del Repositorio


telecom-churn-analisis1/
├── telecom_churn_analysis.ipynb  # Notebook principal (Colab)
├── data/
│   └── TelecomX_Data.json        # Datos originales (API)
├── images/                      # Gráficos guardados
└── README.md                    # Este archivo

 Hallazgos Clave

     26.5% de los clientes abandonan (Churn).

     Clientes nuevos (<20 meses) son más propensos a irse.

     Cargos mensuales altos (>$80) correlacionan con mayor Churn.

     Contratos mensuales tienen 43% de tasa de abandono vs 11% en anuales.

 Dependencias

El proyecto usa las siguientes librerías (instaladas automáticamente en Colab):
python

pandas, numpy, matplotlib, requests

 Recomendaciones

    Fidelizar clientes nuevos: Descuentos en primeros 12 meses.

    Promover contratos anuales: Ofrecer beneficios adicionales.

    Optimizar precios: Revisar planes con cargos >$80.

📄 Licencia

MIT - Libre para uso y modificación.

✉️ Contacto: @tallonson69
Repositorio: github.com/tallonson69/telecom-churn-analisis1
