# 🌍 Mapa Interactivo con Datos del INEGI

Este proyecto muestra un mapa generado a partir de datos obtenidos desde la **API del INEGI**, utilizando **Python**.  
El objetivo es visualizar información estadística de diferentes estados de México de forma geográfica e interactiva.

---

## 🚀 Descripción del proyecto

El script en Python realiza una conexión directa con la API del INEGI, obtiene los datos más recientes de un indicador específico (por ejemplo, población, PIB, producción, etc.) y los representa visualmente en un mapa.

El resultado puede visualizarse desde un archivo HTML generado automáticamente, que se puede abrir en el navegador o publicar en GitHub Pages.

---

## 🧠 Flujo general

1. Conexión a la API del INEGI mediante `requests`.
2. Extracción de los datos por estado (códigos del catálogo de entidades).
3. Limpieza y formateo de la información con `pandas`.
4. Generación de un mapa interactivo con `folium`.
5. Exportación del mapa a un archivo `index.html` para su visualización.

---

## 🧰 Tecnologías utilizadas

- **Python 3**
  - `requests`
  - `pandas`
  - `folium`
- **INEGI API**
- **HTML / Leaflet** (generado automáticamente por Folium)

---
