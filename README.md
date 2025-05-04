# 🗺️ Análisis Geoespacial de Ventas por Tienda con Folium

Este proyecto tiene como objetivo visualizar y analizar la distribución geográfica de ventas realizadas por cuatro tiendas distintas, utilizando coordenadas de latitud y longitud. Se emplea la biblioteca `folium` para generar mapas interactivos que permiten identificar patrones y concentraciones de ventas por ubicación.

---

## 🚀 Descripción

A partir de datos de ventas que incluyen ubicación geográfica, este proyecto:

- Crea mapas individuales para cada tienda utilizando marcadores de color distinto.
- Permite visualizar zonas de alta concentración de ventas.
- Sirve como punto de partida para analizar el rendimiento regional de las tiendas.
- Facilita la toma de decisiones con base en la ubicación de los clientes.

---

## 📊 Variables de Análisis

Cada registro contiene información como:

- `Producto`: Nombre del producto vendido.
- `Categoría del Producto`: Clasificación del producto.
- `Precio`: Precio de venta.
- `Calificación`: Valoración del cliente.
- `lat`, `lon`: Coordenadas geográficas de la compra.

---

## 🧰 Tecnologías Utilizadas

- **Python 3**
- [Pandas](https://pandas.pydata.org/) – Manipulación de datos
- [Matplotlib](https://matplotlib.org/) – Visualización (opcional)
- [Folium](https://python-visualization.github.io/folium/) – Mapas interactivos

---


1. Clona el repositorio:
```bash
git clone https://github.com/tu_usuario/proyecto-tiendas.git
cd proyecto-tiendas
pip install -r requirements.txt
