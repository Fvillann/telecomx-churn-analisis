# 📉 Telecom X – Análisis de Evasión de Clientes (Churn)

Este proyecto fue desarrollado como parte del desafío del curso **Data Science y AI – Alura Latam + Oracle Next Education**.  
El objetivo fue analizar los datos de la empresa **Telecom X**, que enfrenta una alta tasa de cancelación de clientes, y comprender qué factores influyen en esta evasión.

---

## 🎯 Objetivo del Proyecto

- Identificar patrones y características comunes en los clientes que cancelan su servicio.
- Realizar un proceso completo de ETL: extracción, transformación, carga y análisis.
- Generar insights y recomendaciones estratégicas para reducir el churn.

---

## 🛠️ Tecnologías utilizadas

- Python 3.x
- Google Colab
- Pandas
- Matplotlib
- Seaborn

---

## 📁 Estructura del proyecto

- `TelecomX_Churn_Analysis.ipynb`: Notebook principal con el paso a paso del análisis.
- `README.md`: Este archivo con la documentación del proyecto.
- `TelecomX_Data.json`: Archivo fuente con los datos (cargado desde una API externa).

---

## ▶️ Cómo ejecutar el proyecto

1. Abre el notebook en https://colab.research.google.com/drive/1lpMttje9gbpQy6N75gcvkLmcSOStTXNx.
2. Asegúrate de tener conexión a internet para acceder al JSON desde GitHub.
3. Ejecuta cada celda desde la parte superior del notebook.
4. Revisa los gráficos, análisis y conclusiones al final del notebook.

---

## 🔎 Análisis realizado

1. **Extracción de datos** desde una API externa en formato JSON.
2. **Transformación y limpieza** de datos: unificación de columnas, tratamiento de inconsistencias, conversión de tipos.
3. **Análisis exploratorio** de variables categóricas y numéricas para detectar patrones de evasión.
4. **Visualizaciones** con gráficos de barras, boxplots y heatmaps de correlación.
5. **Informe final** con conclusiones y recomendaciones estratégicas.

---

## 📌 Principales conclusiones

- Los contratos mensuales presentan mayor índice de evasión.
- Clientes con menor cantidad de servicios adicionales y menos antigüedad tienden a cancelar.
- Ciertas formas de pago están asociadas con mayor retención.
- El análisis de correlación mostró relaciones interesantes con variables como `costo_diario`, `meses_de_servicio` y `servicios_contratados`.

---

## 💡 Recomendaciones estratégicas

- Ofrecer beneficios en contratos de mayor plazo (trimestral/anual).
- Fomentar paquetes combinados con servicios adicionales (seguridad, soporte, streaming).
- Identificar clientes nuevos o con bajo compromiso para acciones proactivas de retención.

---

## 📍 Estado del proyecto

✅ Proyecto finalizado y entregado como parte del desafío de Alura Latam.  
🔁 Puedes hacer un fork y ampliarlo con modelos de predicción de churn, dashboards o clustering de clientes.

---

## 🤝 Créditos

Desarrollado por Frida Villanueva Medina como parte del programa **ONE – Oracle Next Education + Alura Latam**.
