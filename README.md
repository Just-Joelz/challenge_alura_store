# Desafío del Curso de Alura

# Análisis Comparativo de Tiendas
Este notebook contiene un análisis comparativo de cuatro tiendas, evaluando su desempeño en diferentes aspectos clave para identificar la tienda con el menor desempeño para vender.

## Objetivo del Análisis

El objetivo principal de este análisis es comparar el rendimiento de cuatro tiendas basándose en métricas de ventas, satisfacción del cliente y eficiencia en costos de envío para identificar la tienda con menor desempeño en términos de ventas.

## Datos

Los datos utilizados para este análisis provienen de cuatro archivos CSV, cada uno representando los datos de ventas de una tienda diferente:

- `tienda_1.csv`
- `tienda_2.csv`
- `tienda_3.csv`
- `tienda_4.csv`

Cada archivo contiene información sobre productos, categorías, precios, costos de envío, fechas de compra, vendedores, lugares de compra, calificaciones de clientes, métodos de pago y ubicación geográfica.

## Análisis Realizado

El análisis se llevó a cabo en las siguientes etapas:

1.  **Importación de Datos:** Se cargaron los datos de cada tienda en DataFrames de pandas.
2.  **Análisis de Facturación:** Se calcularon y visualizaron los ingresos totales de cada tienda.
3.  **Ventas por Categoría:** Se analizaron las ventas de productos por categoría en cada tienda y se visualizaron para comparación.
4.  **Calificación Promedio de la Tienda:** Se calculó la calificación promedio de los clientes para cada tienda y se visualizó.
5.  **Productos Más y Menos Vendidos:** Se identificaron y visualizaron los productos más y menos vendidos en cada tienda.
6.  **Envío Promedio por Tienda:** Se calculó y visualizó el costo de envío promedio para cada tienda.

## Conclusiones Principales

Basado en el análisis de los datos, se extrajeron las siguientes conclusiones:

*   La Tienda 1 generó los mayores ingresos totales, mientras que la **Tienda 4** tuvo los menores ingresos totales.
*   Las categorías "Muebles" y "Electrónicos" fueron consistentemente las más vendidas en todas las tiendas.
*   La Tienda 3 tuvo la calificación promedio más alta de los clientes, mientras que la Tienda 1 tuvo la calificación promedio más baja.
*   La **Tienda 4** tuvo el costo de envío promedio más bajo, mientras que la Tienda 1 tuvo el más alto.

Considerando los ingresos totales como el principal indicador de desempeño para vender, la **Tienda 4** es la que mostró el menor desempeño en este conjunto de datos.

## Uso del Notebook

Este notebook puede ser ejecutado secuencialmente para reproducir el análisis y las visualizaciones. Asegúrate de tener las bibliotecas `pandas` y `matplotlib` instaladas.
