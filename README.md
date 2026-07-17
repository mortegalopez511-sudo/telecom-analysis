# telecom-analysis
El proyecto utiliza los siguientes conjuntos de datos:

- **users**: información demográfica de los usuarios (edad, ciudad, fecha de registro y plan).
- **usage**: historial de uso de los clientes, incluyendo llamadas, mensajes y duración de llamadas.

---

## 🛠️ Etapas del análisis

1. Carga e inspección de los datos.
2. Identificación de valores nulos y valores centinela.
3. Limpieza y estandarización de los datos.
4. Revisión y corrección de fechas.
5. Creación de métricas de uso por usuario.
6. Análisis estadístico descriptivo.
7. Visualización mediante histogramas y boxplots.
8. Detección de valores atípicos (outliers).
9. Segmentación de clientes por edad y nivel de uso.
10. Elaboración de conclusiones y recomendaciones para el negocio.

---

## ▶️ Cómo ejecutar el proyecto

### Opción 1: Google Colab

1. Descarga el archivo `.ipynb` del repositorio.
2. Abre Google Colab.
3. Selecciona **Archivo > Subir notebook**.
4. Ejecuta las celdas en orden.

### Opción 2: Jupyter Notebook

1. Clona o descarga este repositorio.
2. Instala las librerías necesarias.
3. Abre el notebook.
4. Ejecuta las celdas de arriba hacia abajo.

---

## 📚 Librerías utilizadas

- pandas
- numpy
- matplotlib
- seaborn

---

## 📈 Principales hallazgos

- Se detectaron valores centinela y fechas fuera del rango esperado que fueron tratados durante la limpieza.
- Los valores nulos encontrados dependían del tipo de registro, por lo que se mantuvieron al formar parte de la estructura de los datos.
- Se identificaron diferentes segmentos de usuarios según su edad y nivel de uso.
- Los valores extremos encontrados representan comportamientos reales de algunos clientes y se conservaron para el análisis.

---

## 👨‍💻 Autor

Miguel Ortega

Proyecto desarrollado como parte del Bootcamp de Data Analysis de TripleTen.
