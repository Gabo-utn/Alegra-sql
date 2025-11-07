# 🧪 Laboratorio ETL + EDA — Egresados Universitarios en Argentina

Este proyecto presenta un flujo completo de **Extracción, Transformación y Análisis Exploratorio de Datos (ETL + EDA)** utilizando Python, pandas y SQLAlchemy, aplicado a un dataset público sobre **egresados universitarios en la República Argentina**.

El trabajo se desarrolló en **Google Colab**, siguiendo buenas prácticas de análisis de datos y documentación.

---

## 🚀 Objetivos del Laboratorio

- Aplicar un proceso completo ETL:
  - ✅ **Extracción** desde Google Drive  
  - ✅ **Transformación y limpieza** del dataset  
  - ✅ **Corrección de tipos y nulos**  
  - ✅ **Creación de nuevas variables derivadas**  
  - ✅ **Carga** en una base SQLite mediante SQLAlchemy  

- Realizar un **EDA completo**:
  - Distribuciones, correlaciones, análisis por categorías
  - Visualizaciones con seaborn y matplotlib

- Responder **3 preguntas de negocio**, entre ellas:
  1. ¿Qué rama tiene más egresados?
  2. ¿Cómo evoluciona el número de egresados en el tiempo?
  3. ¿Cuál es la edad promedio de egreso según género?

- Publicar el trabajo en GitHub con un **notebook ejecutable en Colab**.

---

## 🔗 Abrir en Google Colab

Hacé clic en el botón para ejecutar el notebook directamente:

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Gabo-utn/Alegra-sq/blob/main/lab_egresados.ipynb)

---

## 📂 Contenido del repositorio

---

## 🛠️ Tecnologías utilizadas

- **Python 3**
- **Google Colab**
- **pandas**
- **NumPy**
- **Matplotlib / Seaborn**
- **SQLAlchemy**
- **SQLite**
- **gdown** (para descargar archivos de Google Drive)

---

## 🧩 Pasos principales dentro del notebook

### ✅ ETL
1. Descarga del dataset desde Google Drive con `gdown`
2. Corrección de codificaciones (incluyendo problema de `tamaño_id`)
3. Conversión de tipos y detección de valores faltantes
4. Eliminación de duplicados
5. Creación de variables derivadas:
   - `edad_al_egresar`
   - `antiguedad_egresado`

### ✅ EDA
- Distribución de egresos por año
- Distribución de edades al egresar
- Correlaciones
- Gráficos por rama, género y variables clave

### ✅ Preguntas de negocio respondidas
1. **Rama con mayor cantidad de egresados**
2. **Evolución temporal de los egresados**
3. **Edad promedio al egresar según género**

---

## 📬 Contacto

Si querés ver más trabajos o colaborar:

**Github:** https://github.com/Gabo-utn  
**LinkedIn:** _agregar tu link aquí_  

---

## ✅ Estado del proyecto

✔️ Finalizado y funcional  
✔️ Notebook ejecutable  
✔️ Documentación completa  

---

¡Listo para entregar! 🎓📊✨


