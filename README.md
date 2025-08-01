# Análisis de Evasión de Clientes (Churn)

Este proyecto tiene como objetivo analizar los factores que influyen en la **cancelación del servicio (churn)** por parte de clientes de una empresa de telecomunicaciones. A través de la limpieza, transformación y visualización de datos, se busca generar **insights estratégicos** que permitan reducir la tasa de evasión.

## Objetivo

Comprender los **patrones de comportamiento de los clientes** que abandonan el servicio para desarrollar estrategias de retención más efectivas.

---

## Tecnologías utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Proceso del análisis

### 1. Importación y limpieza de datos
- Carga del archivo JSON.
- Normalización de columnas con diccionarios.
- Conversión de tipos de datos.
- Eliminación de valores nulos y duplicados.
- Corrección de valores inconsistentes (`No phone service → No`, etc.).

### 2. Transformación de datos
- Estandarización de categorías (`Yes` / `No` → `1` / `0`).
- Conversión de `TotalCharges` a tipo numérico.
- Creación de nuevas columnas como `Cuentas_Diarias`.

### 3. Análisis exploratorio
- Análisis descriptivo de variables numéricas y categóricas.
- Visualización de la variable objetivo (`churn`).
- Gráficos comparativos para encontrar correlaciones.

### 4. Conclusiones e insights
- Resumen de hallazgos clave sobre el comportamiento del cliente.
- Identificación de factores asociados al churn.

### 5. Recomendaciones estratégicas
- Acciones sugeridas basadas en los datos para reducir la evasión.

---

## Principales hallazgos

- Clientes con contrato "month-to-month" tienen mayor tasa de evasión.
- Los clientes con bajo tiempo de permanencia (`tenure`) abandonan más.
- Cargos mensuales elevados pueden estar relacionados con churn.
- Los métodos de pago automáticos muestran una menor tasa de evasión.

---

## Próximos pasos sugeridos

- Entrenamiento de modelos de clasificación para predecir el churn.
- Implementación de dashboards con herramientas como Power BI o Tableau.
- Monitoreo en tiempo real de clientes en riesgo.


## Autor

**Jonatan Badilla**  
Especialista en análisis de datos | Python  
📧 jonatan.badilla1127@gmail.com


