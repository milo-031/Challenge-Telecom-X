# 📊 Proyecto: Análisis de Evasión de Clientes (Churn) en Telecom X | Challenge Alura Latam  

Este proyecto forma parte del **Challenge de Ciencia de Datos de Alura Latam**, donde se desarrolla un **Análisis Exploratorio de Datos (EDA)** para comprender los factores que influyen en la **evasión de clientes (churn)** en una empresa de telecomunicaciones ficticia: **Telecom X**.  

El objetivo es identificar patrones de comportamiento, descubrir insights y proponer **estrategias de retención efectivas** que ayuden a reducir el abandono de clientes en un sector altamente competitivo.  

---

## 👩‍💻 Autor  

- **Nombre:** Milagros Yucra  
- **Mail:** *[tu correo aquí]*  
- **GitHub:** [MilagrosYucra](https://github.com/MilagrosYucra)  

---

## 📋 Descripción del Proyecto  

El notebook **`TelecomX_LATAM.ipynb`** contiene el análisis paso a paso de datos de clientes simulados, obtenidos desde una **API en formato JSON**.  

En este estudio se abordan preguntas clave como:  

- ¿Qué perfil demográfico y de consumo tienen los clientes que cancelan?  
- ¿Cómo influyen el **tipo de contrato** y el **método de pago** en la tasa de churn?  
- ¿Qué relación existe entre **antigüedad, cargos y evasión**?  
- ¿La cantidad de servicios contratados fortalece la lealtad del cliente?  

Finalmente, se presentan **conclusiones y recomendaciones estratégicas** basadas en datos para ayudar a la empresa a **retener clientes valiosos**.  

---

## ⚙️ Aspectos Técnicos  

✔️ **Extracción de datos** desde API en formato JSON.  
✔️ **Limpieza y preprocesamiento** (inconsistencias, valores vacíos, estandarización de variables).  
✔️ **Transformación y enriquecimiento** de datos:  
   - Creación de variables como `Costo_Diario`.  
   - Conversión de `Churn` a formato binario.  
   - Normalización de datos anidados con `pandas.json_normalize`.  
✔️ **Análisis descriptivo** con métricas agregadas.  
✔️ **Visualizaciones dinámicas y claras** con **Matplotlib** y **Seaborn**.  
✔️ **Informe final estructurado** con insights y estrategias de retención.  

---

## 🛠️ Tecnologías Utilizadas  

- **Python 3**  
- **Pandas** – análisis y manipulación de datos  
- **Matplotlib** – visualización estática  
- **Seaborn** – visualización estadística y estética  
- **Jupyter Notebook / Google Colab**  

---

## ✅ Requisitos del Challenge Cumplidos  

- Carga y transformación de datos desde JSON.  
- Limpieza de inconsistencias en la columna `Churn`.  
- Creación de nuevas variables y estandarización de categorías.  
- Exploración descriptiva con `describe()`.  
- Visualización de **proporción de churn** y análisis por variables.  
- Correlaciones con **heatmaps** y gráficos adicionales.  
- **Informe final con conclusiones y recomendaciones estratégicas.**  

---

## 📊 Estructura del Notebook  

1. **📌 Extracción de datos**  
2. **🔧 Transformación y limpieza**  
3. **📊 Análisis exploratorio (EDA)**  
   - Estadísticas descriptivas  
   - Distribución de churn  
   - Análisis por variables categóricas  
   - Análisis por variables numéricas  
4. **📍 Análisis extra: Correlaciones**  
5. **📄 Informe final: conclusiones y recomendaciones**  

---

## 🌟 Principales Insights  

- 🔑 **Contrato mes a mes** → el predictor más fuerte del churn.  
- ⏳ **Clientes nuevos** (baja antigüedad) → más propensos a cancelar.  
- 💳 **Método de pago con cheque electrónico** → mayor riesgo de evasión.  
- 💲 **Cargos mensuales altos** → correlacionan con cancelación, sobre todo si no se percibe valor añadido.  
- 📦 **Cantidad de servicios contratados**: los clientes con **3 a 6 servicios** muestran mayor lealtad; demasiados o muy pocos aumentan la evasión.  

---

## 🎯 Recomendaciones Estratégicas  

1. **Incentivar contratos a largo plazo** con descuentos y beneficios.  
2. **Programa de bienvenida** para nuevos clientes (onboarding, soporte proactivo).  
3. **Optimizar métodos de pago** → premiar a clientes que migren a pagos automáticos.  
4. **Venta cruzada inteligente**, enfocada en valor percibido y no en sobrecarga de servicios.  
5. **Sistema de alertas tempranas** para identificar clientes de alto riesgo y actuar antes de la cancelación.  

---

## 🚀 Próximos pasos  

Este análisis exploratorio sienta las bases para:  

- Construcción de **modelos predictivos de churn**.  
- Desarrollo de **dashboards interactivos** en Streamlit o Power BI.  
- Aplicación de **segmentación de clientes** para personalizar estrategias de retención.  

---

## 💡 Conclusión  

La **evasión de clientes** no solo afecta los ingresos, también incrementa los costos de adquisición de nuevos usuarios.  

Este proyecto permitió identificar patrones claros y proponer **acciones estratégicas** que, de implementarse, podrían **reducir significativamente la tasa de churn en Telecom X**.  

Con estos hallazgos, se abre el camino hacia el uso de modelos de Machine Learning y herramientas de BI para una toma de decisiones aún más sólida.  

---

👩‍💻 *Proyecto desarrollado por **Milagros Yucra** como parte del Challenge de Ciencia de Datos de Alura Latam.*
