# Proyecto Telecom 

# 📊 Análisis del Abandono de Clientes (Churn)

El presente análisis tiene como objetivo explorar el fenómeno de **evasión de clientes**, también conocido como **"churn"** —es decir, aquellos usuarios que han decidido cancelar su servicio. Comprender las **causas y patrones asociados a la cancelación** es clave para desarrollar estrategias efectivas de retención y así reducir la pérdida de clientes. 🔍

## 🛠️ Tecnologías utilizadas

- **Python** como lenguaje principal.
- **Pandas** para manipulación y tratamiento de datos.
- **Plotly Express** para visualizaciones interactivas.
- Formato de entrada: **JSON** (estructura anidada).
- Google Colab

## 📥 Preparación de los datos

1. El dataset original fue proporcionado en formato **`.json`**, el cual contenía múltiples columnas anidadas.
2. Se utilizó la función `json_normalize` de **Pandas** para **transformar y aplanar** la estructura, obteniendo un **DataFrame tabular** listo para el análisis.
3. Se realizó una **exploración inicial** para identificar posibles **valores nulos o vacíos**, asegurando la integridad de los datos.
4. Finalmente, se aplicó una **reestructuración del dataset** con el fin de mejorar su legibilidad y facilitar futuras visualizaciones y modelos analíticos.

✅ Este procesamiento preparó el terreno para un análisis profundo del comportamiento de abandono, permitiendo identificar **tendencias clave** como la relación entre el tiempo de permanencia (`tenure`) y la tasa de cancelación.

---

