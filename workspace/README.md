# Análisis de Red de Tiendas

Este proyecto realiza un análisis de datos de una red de tiendas utilizando Python con las librerías Pandas y Numpy. Se analizan las ventas, inventarios y satisfacción de clientes para obtener insights sobre el rendimiento de las tiendas.

## Archivos del Proyecto

- `sales.csv`: Datos de ventas por tienda y producto.
- `inventories.csv`: Datos de inventarios disponibles por tienda y producto.
- `satisfaction.csv`: Datos de satisfacción de clientes por tienda.
- `analisis_red_tiendas.ipynb`: Notebook de Jupyter con el análisis completo.

## Requisitos

- Python 3.x
- Pandas
- Numpy
- Jupyter Notebook

## Instalación

1. Instala las dependencias:
   ```
   pip install pandas numpy jupyter
   ```

2. Abre el notebook:
   ```
   jupyter notebook analisis_red_tiendas.ipynb
   ```

3. Ejecuta las celdas en orden para realizar el análisis.

## Análisis Realizado

- Carga y limpieza de datos.
- Cálculos de ventas totales por producto y tienda.
- Ingresos totales por tienda.
- Resumen estadístico de ventas.
- Promedio de ventas por categoría.
- Rotación de inventarios.
- Análisis de satisfacción de clientes.
- Cálculos con Numpy: mediana, desviación estándar, proyecciones aleatorias.

## Resultados

El notebook genera varios DataFrames y métricas que ayudan a identificar tiendas con bajo rendimiento, niveles críticos de inventario y oportunidades de mejora en satisfacción de clientes.