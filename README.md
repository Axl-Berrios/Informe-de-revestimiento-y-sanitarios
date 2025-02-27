# Informe-de-revestimiento-y-sanitarios
Este informe analiza ventas, márgenes y clientes en revestimiento y sanitarios. Utiliza modelos predictivos, segmentación y evaluación de inventarios para identificar tendencias y mejorar la rentabilidad, optimizando ventas y retención de clientes.
# Análisis de Ventas, Inventario, Clientes y Logística

Este proyecto se centra en el análisis de datos de ventas, inventario, clientes y logística utilizando Python y bibliotecas como Pandas, Matplotlib, Seaborn y Statsmodels. El objetivo es extraer información valiosa que ayude a la toma de decisiones en el negocio.

## Contenido

1. [Introducción](#introducción)
2. [Análisis de Ventas](#análisis-de-ventas)
3. [Análisis de Inventario](#análisis-de-inventario)
4. [Análisis de Clientes](#análisis-de-clientes)
5. [Análisis de Logística](#análisis-de-logística)
6. [Requisitos](#requisitos)
7. [Ejecutar el Proyecto](#ejecutar-el-proyecto)
8. [Conclusiones](#conclusiones)

## Introducción

Este proyecto tiene como objetivo analizar los datos históricos de ventas, inventario, clientes y logística para identificar tendencias, patrones y oportunidades de mejora en el negocio.

## Análisis de Ventas

- **Carga de Datos**: Se cargan los datos de ventas desde un archivo CSV.
- **Análisis Temporal**: Se realizan análisis de series temporales para identificar tendencias y estacionalidades en las ventas.
- **Visualización**: Se generan gráficos que muestran la evolución de las ventas a lo largo del tiempo, así como la comparación entre diferentes años.
- **Predicciones**: Se utilizan modelos ARIMA y Prophet para realizar predicciones de ventas futuras.

## Análisis de Inventario

- **Carga de Datos**: Se cargan los datos de inventario desde un archivo CSV.
- **Análisis de Ventas por Producto**: Se analizan las ventas totales y márgenes por producto.
- **Visualización**: Se generan gráficos que muestran los productos más vendidos y su rentabilidad.
- **Predicciones**: Se utilizan modelos de suavizamiento exponencial para predecir las ventas futuras.

## Análisis de Clientes

- **Carga de Datos**: Se cargan los datos de clientes desde un archivo CSV.
- **Análisis RFM**: Se realiza un análisis de Recencia, Frecuencia y Valor Monetario para segmentar a los clientes.
- **Identificación de Clientes Inactivos**: Se identifican clientes que no han realizado compras recientes.
- **Visualización**: Se generan gráficos que muestran la distribución de clientes por segmento y recencia.

## Análisis de Logística

- **Carga de Datos**: Se cargan los datos de logística desde un archivo CSV.
- **Análisis de Costos**: Se analizan los costos de logística, incluyendo costos con y sin peaje.
- **Visualización**: Se generan gráficos que muestran la tendencia de costos y la distribución de distancias recorridas.

## Requisitos

Para ejecutar este proyecto, necesitarás tener instaladas las siguientes bibliotecas de Python:

- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- prophet
- scikit-learn

Puedes instalar las bibliotecas necesarias utilizando pip:

```bash
pip install pandas numpy matplotlib seaborn statsmodels prophet scikit-learn
