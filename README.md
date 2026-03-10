# 📊 Telecom X – Predicción de Cancelación de Clientes (Churn)

Proyecto de **Machine Learning aplicado al análisis de cancelación de clientes** para la empresa ficticia Telecom X.

Este proyecto corresponde a la **Parte 2 del desafío de Data Science**, donde se desarrollan modelos predictivos capaces de identificar clientes con mayor probabilidad de cancelar sus servicios.

El objetivo principal es **anticipar la cancelación (churn)** y proporcionar **insights estratégicos que permitan mejorar la retención de clientes**.

---

# 🎯 Objetivo del Proyecto

Construir un pipeline de Machine Learning que permita:

* Preparar los datos para modelado predictivo
* Analizar relaciones entre variables y cancelación
* Entrenar modelos de clasificación
* Evaluar el rendimiento de los modelos
* Interpretar los factores que influyen en la cancelación
* Proponer estrategias de retención basadas en datos

---

# 📂 Estructura del Proyecto

El proyecto se organiza en las siguientes etapas:

## 1️⃣ Preparación de los Datos

* Carga del dataset previamente tratado
* Eliminación de columnas irrelevantes
* Transformación de variables categóricas mediante **One-Hot Encoding**
* Análisis de proporción de cancelación (Churn)
* Preparación de variables predictoras y variable objetivo

## 2️⃣ Correlación y Selección de Variables

* Análisis de **correlación entre variables**
* Identificación de variables con mayor relación con la cancelación
* Análisis dirigido mediante visualizaciones como **boxplots**

## 3️⃣ Modelado Predictivo

* División del dataset en **entrenamiento y prueba**
* Entrenamiento de modelos de Machine Learning:

  * **Regresión Logística**
  * **Random Forest**
* Evaluación utilizando métricas de clasificación:

  * Accuracy
  * Precision
  * Recall
  * F1-score
  * Matriz de confusión

## 4️⃣ Interpretación y Conclusiones

* Análisis de **importancia de variables**
* Identificación de factores clave que influyen en la cancelación
* Propuestas de **estrategias de retención de clientes**

---

# 📊 Resultados Principales

Los modelos desarrollados alcanzaron una **exactitud cercana al 79%**, mostrando una capacidad sólida para predecir clientes con riesgo de cancelación.

El modelo de **Regresión Logística** fue seleccionado como modelo principal debido a su **interpretabilidad**, permitiendo comprender con mayor claridad qué variables impactan en la cancelación.

---

# 🔎 Factores más influyentes en la cancelación

El análisis del modelo identificó los siguientes factores clave:

* **Antigüedad del cliente**
  Clientes con menor tiempo en la empresa presentan mayor probabilidad de cancelar.

* **Tipo de contrato**
  Los contratos mensuales tienen una tasa de cancelación significativamente mayor que los contratos anuales.

* **Servicio de internet por fibra óptica**
  Los clientes con este servicio presentan mayor probabilidad de abandono.

* **Servicios adicionales**
  Variables relacionadas con streaming o múltiples líneas influyen en el comportamiento del cliente.

* **Método de pago y facturación**
  Determinados métodos de pago se asocian con mayores niveles de cancelación.

---

# 💡 Recomendaciones Estratégicas

A partir de los resultados del modelo, se sugieren las siguientes estrategias:

### 🔹 Mejorar la experiencia de clientes nuevos

Implementar programas de onboarding y seguimiento durante los primeros meses.

### 🔹 Incentivar contratos de mayor duración

Ofrecer descuentos o beneficios para contratos de 1 o 2 años.

### 🔹 Evaluar el servicio de fibra óptica

Analizar posibles problemas de calidad o expectativas no satisfechas.

### 🔹 Promover servicios de valor agregado

Paquetes con servicios adicionales pueden aumentar la fidelización.

### 🔹 Implementar alertas de churn

Utilizar el modelo predictivo para identificar clientes con alto riesgo y aplicar estrategias de retención.

---

# 🛠️ Tecnologías Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

# 📈 Modelos Utilizados

Los modelos entrenados en el proyecto fueron:

**Regresión Logística**

* Modelo interpretable
* Permite analizar impacto de variables

**Random Forest**

* Modelo basado en árboles
* Robusto ante relaciones no lineales

---

# ⚙️ Instalación y Uso

## 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/matijairv/challenge2-parte2-data-science-LATAM.git
```

## 2️⃣ Acceder al proyecto

```bash
cd challenge2-parte2-data-science-LATAM
```

## 3️⃣ Instalar dependencias

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 4️⃣ Ejecutar el notebook

Abrir el notebook en **Jupyter Notebook** o **Google Colab** y ejecutar las celdas en orden.

---

# 📁 Dataset

El dataset utilizado corresponde al desafío **Telecom X – Churn**, previamente tratado en la **Parte 1 del proyecto**.

Incluye información sobre:

* características demográficas de los clientes
* servicios contratados
* tipo de contrato
* métodos de pago
* comportamiento de facturación
* variable objetivo **Abandono (Churn)**

---

# 👨‍💻 Autor

**matijairv**

Proyecto desarrollado como parte del programa **Oracle Next Education (ONE) + Alura Latam – Data Science**.

---
