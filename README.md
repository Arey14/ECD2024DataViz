# ECD2024 Data Visualization 📊

[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue?style=flat-square&logo=python)](https://www.python.org/)
[![Data Analysis](https://img.shields.io/badge/Data-Analysis-green?style=flat-square&logo=pandas)](https://pandas.pydata.org/)
[![Visualization](https://img.shields.io/badge/Data-Visualization-orange?style=flat-square&logo=plotly)](https://plotly.com/)

## 📌 Descripción del Proyecto

Este repositorio contiene un análisis detallado y visualizaciones interactivas del conjunto de datos [Precios en Surtidor](https://datos.gob.ar/dataset/energia-precios-surtidor---resolucion-3142016) proporcionado por el gobierno argentino. El objetivo es proporcionar insights valiosos sobre la evolución y distribución de los precios de combustibles en Argentina.

## 🔍 Contenido del Análisis

### 1. Análisis Exploratorio de Datos (EDA)
- Estadísticas descriptivas
- Análisis de tendencias temporales
- Identificación de patrones y anomalías
- Frecuencia de precios

👉 **[Ver EDA Completo](https://arey14.github.io/ECD2024DataViz/EDA.html)**

- Datos historicos: 2820824
- Fechas con datos consistentes tomados en historicos: 2017 a 2024
- Datos surtidor: 36706

- Features Usadas para los graficos:
  - Tiempo
  - Precio
  - Tipo de producto
  - Provincia

### 2. Stacked Area Relativo - Pregunta 1: ¿Se ve un cambio de precios relativos entre los productos? ¿Cual es el producto más caro en el tiempo?
- Análisis comparativo entre diferentes tipos de combustibles
- Evolución temporal de precios relativos

📊 **[Ver Análisis de Precios](https://arey14.github.io/ECD2024DataViz/stacked_area_chart.html)**

### 3. Bump Chart - Pregunta 2: ¿Que provincias fueron las que tuvieron los precios más caros?
#### Parte 1: Top 5 Provincias
- Visualización dinámica de las principales provincias
- Cambios en rankings a lo largo del tiempo
- Patrones de comportamiento provincial
* Interpolación lineal para provincias con datos faltantes

🏆 **[Ver Bump Chart Top 5](https://arey14.github.io/ECD2024DataViz/Bump%20chart%20top%205.html)**

#### Parte 2: ¿Como era el ranking entre las provincias con datos completos?
- Visualización Bump Chart de provincias con datos más completos

📈 **[Ver Análisis Provincial Completo](https://arey14.github.io/ECD2024DataViz/bump%20chart%20provincias%20con%20datos%20completos.html)**

### 4. Heat Map - ¿En donde están distribuidas las surtidoras dentro del país?
- Densidad de estaciones por región
- Identificación de zonas de alta y baja cobertura

🗺️ **[Ver Heat Map Interactivo](https://arey14.github.io/ECD2024DataViz/heatmap.html)**

## 🛠️ Tecnologías Utilizadas

- Python
- Pandas
- Plotly
- Seaborn
- Folium
- Jupyter Notebooks

## 📥 Cómo Utilizar

1. Clone el repositorio:
```bash
git clone https://github.com/arey14/ECD2024DataViz.git
```

2. Instale las dependencias necesarias:
```bash
pip install -r requirements.txt
```

3. Explore los notebooks y visualizaciones en el orden sugerido arriba.



## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si desea contribuir:

1. Haga fork del repositorio
2. Cree una nueva rama (`git checkout -b feature/analysis`)
3. Realice sus cambios
4. Commit sus cambios (`git commit -am 'Add some analysis'`)
5. Push a la rama (`git push origin feature/analysis`)
6. Cree un Pull Request

## 📝 Licencia

Este proyecto está bajo la Licencia MIT - vea el archivo [LICENSE.md](LICENSE.md) para más detalles.

## 📧 Contacto

Para preguntas o sugerencias, no dude en abrir un issue o contactar directamente.

---
⭐ Si este proyecto le resulta útil, considere darle una estrella en GitHub.
