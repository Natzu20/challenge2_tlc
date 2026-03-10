# Análisis de Evasión de Clientes – Telecom

## Descripción
Este proyecto analiza la **evasión de clientes (Churn)** en Telecom X, una empresa de telecomunicaciones. El objetivo es identificar patrones y factores que afectan la permanencia de los clientes, sirviendo como base para un análisis predictivo y estrategias de retención.

Se emplean técnicas de **limpieza y transformación de datos**, **análisis exploratorio** y **visualización**, utilizando herramientas como Python, Pandas, Matplotlib y Plotly.

---

## Diccionario de datos 

- `ID_Cliente`: identificador único de cada cliente  
- `Churn`: indica si el cliente dejó (1) o permaneció (0) en la empresa  
- `Genero`: género del cliente (Male/Female)  
- `Adulto_Mayor`: 1 si el cliente tiene 65 años o más, 0 si no  
- `Pareja`: 1 si el cliente tiene pareja, 0 si no  
- `Dependientes`: 1 si el cliente tiene dependientes, 0 si no  
- `Meses_Cliente`: duración del contrato en meses  
- `Servicio_Telefono`: 1 si el cliente tiene servicio telefónico, 0 si no  
- `Lineas_Adicionales`: 1 si tiene más de una línea telefónica, 0 si no  
- `Servicio_Internet`: tipo de servicio de internet (DSL, Fiber optic, No)  
- `Seguridad_Online`: 1 si tiene seguridad online, 0 si no  
- `Backup_Online`: 1 si tiene respaldo online, 0 si no  
- `Proteccion_Dispositivo`: 1 si tiene protección del dispositivo, 0 si no  
- `Soporte_Tecnico`: 1 si tiene soporte técnico, 0 si no  
- `Streaming_TV`: 1 si tiene streaming de TV, 0 si no  
- `Streaming_Peliculas`: 1 si tiene streaming de películas, 0 si no  
- `Contrato`: tipo de contrato (Month-to-month, One year, Two year)  
- `Facturacion_Sin_Papel`: 1 si prefiere factura online, 0 si no  
- `Metodo_Pago`: forma de pago del cliente  
- `Facturacion_Mensual`: total de todos los servicios del cliente por mes  
- `Facturacion_Total`: total gastado por el cliente  
- `Gasto_Diario`: promedio diario calculado a partir de la facturación mensual  

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
