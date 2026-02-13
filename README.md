# Sprint 7: Análisis Integral de Telecomunicaciones - ConnectaTel
Este proyecto final aplica técnicas avanzadas de Análisis Exploratorio de Datos (EDA), limpieza, visualización y segmentación de clientes para una empresa de telecomunicaciones líder en Latinoamérica. El objetivo principal es transformar datos brutos en perfiles estadísticos accionables para mejorar la retención y optimizar los planes comerciales.

## 📊 Resumen del Proyecto
El análisis se centra en el comportamiento de los usuarios hasta el año 2024, integrando información de planes, perfiles de clientes y uso real de servicios (llamadas y mensajes).

## 🛠️ Tecnologías Utilizadas
Python: Lenguaje principal de análisis.

Pandas & NumPy: Manipulación de datos y cálculos lógicos de segmentación.

Seaborn & Matplotlib: Visualización de distribuciones, detección de outliers y análisis comparativo por plan.

## 🔍 Hallazgos Clave (Insights)
### ➡️ Esto sugiere que...
Comportamiento agnóstico al plan: La distribución de uso (mensajes y minutos) es casi idéntica entre los planes Básico y Premium. Esto indica que el plan contratado no es el factor que limita o incentiva el volumen de consumo para el usuario promedio.

Madurez del mercado: El segmento dominante es el de Adultos (30-60 años) con una distribución de edad uniforme, lo que refleja una base de clientes estable y predecible.

Potencial de Upselling: La presencia de Heavy Users (outliers de alto consumo) en el plan Básico revela una oportunidad directa para migrar clientes a planes superiores que se ajusten mejor a su realidad de uso.

### 💡 Recomendaciones Estratégicas
Optimización de Planes: Revisar la propuesta de valor del plan Premium, ya que los datos sugieren que los usuarios no consumen significativamente más que en el plan Básico.

Estrategia de Segmentación: Priorizar campañas de fidelización para el grupo de Uso Medio, que representa la mayor masa crítica de la empresa.

Tratamiento de Datos: Mantener los valores atípicos de consumo en los modelos de predicción de ingresos, dado que representan comportamientos reales de los clientes más rentables.

## 📂 Estructura del Repositorio
plans.csv: Información técnica y comercial de los planes.

users.csv: Datos demográficos y fechas de registro de clientes.

usage.csv: Registro detallado de cada interacción de voz y texto.

S7 Version-Estudiante-Project-ConnectaTel.ipynb: Proceso completo de limpieza, EDA y segmentación paso a paso.
