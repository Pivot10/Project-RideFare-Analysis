# 🚕 Project RideFare: Análisis de Precios Uber & Lyft (ESPOL)

## 📌 Descripción
¿Cómo afecta el clima de Boston al precio de un viaje? Este proyecto analiza un dataset de **693,071 registros** para identificar patrones de precios dinámicos (Surge Multiplier) en las plataformas Uber y Lyft.

## 🎯 Objetivos del Análisis
- Evaluar la correlación entre variables climáticas (`temp`, `rain`, `humidity`) y el costo del viaje.
- Comparar la estabilidad de precios entre Uber y Lyft bajo condiciones extremas.
- Identificar zonas geográficas con mayor sensibilidad a cambios de tarifa.

## 🛠️ Stack Tecnológico
- **Python 3.x**
- **Pandas:** Limpieza de datos y feature engineering (creación de `price_per_km`).
- **Matplotlib & Seaborn:** Visualización de distribuciones y correlaciones.
- **Jupyter Notebook:** Entorno de desarrollo.

## 💡 Insights Clave
- **Impacto del Clima:** Se detectó que la lluvia fuerte activa el `surge_multiplier`, incrementando las tarifas en un promedio del 12% en rutas específicas.
- **Diferenciación de Marca:** Uber mostró mayor estabilidad de precios ante cambios climáticos leves, mientras que Lyft ajusta sus tarifas con mayor frecuencia.
- **Zonificación:** Las estaciones de origen y destino influyen más en el precio final que la temperatura actual.

## 📂 Estructura del Repositorio
- `/data`: (Opcional) Enlace al dataset original.
- `/notebooks`: Jupyter Notebook con el análisis exploratorio (EDA).
- `/img`: Gráficos y visualizaciones generadas.

---
**Piagget Obando Troya** | *Data Driven Decision Specialist - ESPOL*
