# Análisis de Evasión de Clientes – Telecom

## Descripción
Este proyecto analiza la **evasión de clientes (Churn)** en Telecom X, una empresa de telecomunicaciones. El objetivo es identificar patrones y factores que afectan la permanencia de los clientes, sirviendo como base para un análisis predictivo y estrategias de retención.

Se emplean técnicas de **limpieza y transformación de datos**, **análisis exploratorio** y **visualización**, utilizando herramientas como Python, Pandas, Matplotlib y Plotly.

---

## Objetivos
- Comprender la distribución de Churn dentro de la base de clientes.  
- Identificar variables categóricas y numéricas asociadas con la evasión.  
- Extraer insights que ayuden a reducir la pérdida de clientes.  
- Proponer recomendaciones estratégicas basadas en el análisis.

---

## Contenido del proyecto
- **Extracción de datos**: Se normaliza un archivo JSON y se consolida en un DataFrame unificado.  
- **Limpieza y transformación**: Conversión de tipos de datos, codificación binaria, manejo de valores nulos e inconsistencias.  
- **Análisis exploratorio**: Distribución de Churn, análisis por variables categóricas y numéricas, visualizaciones interactivas.  
- **Conclusiones y recomendaciones**: Insights sobre factores de riesgo y sugerencias estratégicas para la retención de clientes.

---

## Visualizaciones
- Distribución general de clientes por Churn (barras y pastel).  
- Proporción de Churn según variables categóricas: género, tipo de contrato, método de pago, servicio de internet.  
- Distribución de variables numéricas (Meses de Cliente, Facturación Mensual, Facturación Total, Gasto Diario) según Churn.

---

## Resultados Clave
- Los **contratos cortos (Month-to-month)** y ciertos **métodos de pago** están asociados con mayor Churn.  
- La **antigüedad del cliente** es un factor relevante: clientes recientes presentan mayor riesgo.  
- Clientes con **servicio Fiber optic** presentan mayor probabilidad de abandonar.

---

## Recomendaciones
1. Implementar estrategias de fidelización para contratos Month-to-month.  
2. Campañas de retención para clientes con Fiber optic.  
3. Monitoreo activo de clientes nuevos para ofrecer asistencia temprana.  
4. Analizar métodos de pago para mejorar la experiencia y reducir fricciones.  
5. Desarrollar un modelo predictivo de Churn basado en las variables más relevantes.

---

## Tecnologías Utilizadas
- Python 3  
- Pandas  
- Matplotlib  
- Seaborn  
- Plotly  

---

## Autor
**Natalia Puerto** 

---

## Licencia
Este proyecto se comparte con fines educativos y de análisis de datos. Puedes utilizarlo y adaptarlo respetando la autoría.
