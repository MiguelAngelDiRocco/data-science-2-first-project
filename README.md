# Predicción de PM2.5 mediante Machine Learning
## Análisis Global de Factores Meteorológicos y Socioeconómicos

**Carrera:** Data Science II  
**Institución:** Coderhouse  
**Alumno:** Miguel Ángel Di Rocco  
**Entrega:** Primera Entrega - Análisis Exploratorio y Feature Engineering  
**Fecha de Entrega:** 21/10/2025

---

## 🔗 Enlaces al Proyecto

📓 **Notebook Principal:** [Google Colab](https://colab.research.google.com/drive/1fyTevP6IlGcZjw8F28g9cc_LqmaCPa_s?usp=sharing) 
📊 **Dataset Original:** [Global Weather Repository - Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository)
   **Presentación:** [Presentación](https://www.canva.com/design/DAG2XdBF6fg/A1VKKW1ImAroj47nZuVKyg/view?utm_content=DAG2XdBF6fg&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=he608a2bdae)
---

## 📋 Descripción General

Este proyecto tiene como objetivo **predecir concentraciones de material particulado fino (PM2.5)** a nivel global, analizando la influencia de factores meteorológicos, temporales y socioeconómicos.

### **Contexto del Problema**

La contaminación por PM2.5 es uno de los principales riesgos para la salud pública según la OMS, causando más de **4 millones de muertes prematuras anuales**. Comprender los factores que influyen en su concentración es crítico para:
- Sistemas de alerta temprana en salud pública
- Políticas de control de emisiones
- Planificación urbana sostenible

### **Alcance de esta Entrega (1/2)**

Esta primera entrega se centra en:
1. **Exploración y limpieza** de datos climáticos globales
2. **Análisis exploratorio exhaustivo** (EDA) para identificar patrones y relaciones
3. **Feature Engineering** para preparar variables predictivas óptimas
4. **Validación de hipótesis** sobre factores que influyen en PM2.5

**Próxima entrega:** Modelado predictivo con múltiples algoritmos de ML, validación cruzada y análisis de errores.

---

## 📊 Dataset
  
**Enriquecimiento externo:** API RestCountries (población y densidad)  
**Período de datos:** Mayo 2024 - Abril 2025 (12 meses)  
**Cobertura geográfica:** 190 países

### **Dimensiones del Dataset Final**
- **Registros:** 78,238 (después de filtrado de outliers)
- **Variables:** 13 (1 target + 12 features)
- **Variable objetivo:** `pm25_log` - Concentración de PM2.5 transformada logarítmicamente

### **Variables Predictivas Clave**
- **Meteorológicas:** Velocidad del viento, temperatura, humedad, nubosidad, UV, precipitación
- **Temporales:** Mes, hora del día (estacionalidad y patrones diurnos)
- **Socioeconómicas:** Densidad poblacional por país
- **Binarias derivadas:** Indicadores de lluvia y viento fuerte (threshold effects)

---

**Librerías principales:**
- `pandas` 2.0+ → Manipulación de datos
- `numpy` 1.24+ → Operaciones numéricas
- `plotly` 5.17+ → Visualizaciones interactivas
- `scipy` 1.11+ → Estadística inferencial (t-tests, distribuciones)
- `scikit-learn` 1.3+ → Preprocesamiento y validación VIF
- `requests` 2.31+ → Consultas a API RestCountries

**Entorno de desarrollo:**
- Google Colab
  
---

## 📫 Contacto

**Miguel Ángel Di Rocco**  
📧 Email: [migueldirocco.ds@gmail.com](mailto:migueldirocco.ds@gmail.com)  
🔗 LinkedIn: (https://www.linkedin.com/in/miguelangeldirocco/)  
🐙 GitHub: [MiguelAngelDiRocco](https://github.com/MiguelAngelDiRocco)

---

## ✅ Estado del Proyecto

🚧 **En desarrollo**  
📅 **Entrega 1:** ✔️ Completada (EDA + Feature Engineering)  
📅 **Entrega 2:** 🔄 En progreso (Modelado + Validación) - Entrega prevista: [A definir]

---

## 📜 Licencia

Este proyecto es de uso académico para el curso de Data Science II de Coderhouse.

---

## 🙏 Agradecimientos

- **Coderhouse** por la formación en Data Science
- **RestCountries API** por los datos poblacionales
- Comunidad de **Kaggle** por compartir el dataset original

---

⭐ Si este proyecto te resultó útil, ¡considera darle una estrella en GitHub!
