# Análisis de Evasión de Clientes - Telecom X

Este proyecto forma parte del Challenge de la etapa 2 del programa Oracle ONE - Alura Latam.

## 🎯 Objetivo

Analizar los datos de clientes de una empresa de telecomunicaciones para entender los factores que influyen en la **evasión de clientes (churn)** y así facilitar estrategias de retención.

---

## 🔄 Limpieza y Tratamiento de Datos

Se realizaron los siguientes pasos:

- Importación de datos y análisis inicial
- Conversión de variables categóricas a numéricas con `LabelEncoder` y `get_dummies`
- Tratamiento de nulos con regresión lineal para la columna `Charges.Total`
- Creación de nueva variable: `Cuentas_Diarias` (gasto mensual / 30)
- Estandarización de columnas y renombramiento

---

## 📊 Análisis Exploratorio de Datos

- Distribución de churn (`Churn`) en gráfico de torta
- Análisis descriptivo: media, mediana, desviación estándar
- Distribución de evasión por:
  - Variables categóricas (ej: género, contrato, método de pago)
  - Variables numéricas (ej: tenure, gasto total)
- Análisis de correlación entre variables

---

## 🔍 Conclusiones e Insights

- Los clientes con contrato mes a mes, método de pago con cheque electrónico y servicio de fibra óptica tienen mayor propensión a la evasión.
- La falta de servicios como soporte técnico o respaldo online también se asocia con mayor churn.
- La variable `tenure` tiene una correlación negativa fuerte con el churn: a mayor tiempo, menor probabilidad de evasión.

---

## 💡 Recomendaciones

- Fomentar la migración a contratos anuales o bianuales con beneficios exclusivos.
- Incentivar el uso de servicios adicionales como soporte técnico o protección de dispositivos.
- Reforzar campañas con clientes nuevos durante los primeros meses (cuando el churn es más alto).
- Automatizar alertas para clientes con métodos de pago de mayor riesgo.

---

## 📁 Archivos incluidos

- `telecom_churn_analysis.ipynb`: Notebook con todo el análisis realizado.
- `README.md`: Este archivo.
- Archivos de apoyo (si los agregaste, como CSV o visualizaciones exportadas).

---

## 🚀 Autor

**Jacob Alarcón** – Estudiante de Ingeniería Comercial | Oracle ONE G8 – Alura Latam

---

