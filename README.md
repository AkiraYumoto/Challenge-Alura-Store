# Challenge-Alura-Store

# Análisis Comparativo de Tiendas para Decisión Estratégica

## 1. Descripción del Proyecto 🎯

Este proyecto es un análisis de datos exploratorio (EDA) de cuatro tiendas, con el objetivo de evaluar su rendimiento general y proporcionar una recomendación de negocio basada en datos. El análisis se enfoca en métricas clave de ventas, finanzas y experiencia del cliente para identificar qué tienda es la menos rentable y, por lo tanto, la principal candidata a ser vendida para optimizar recursos.

## 2. Objetivo del Análisis ❓

El Sr. Juan, propietario de las cuatro tiendas, busca optimizar su negocio. El objetivo principal de este informe no es encontrar la "mejor" tienda, sino **identificar cuál de las cuatro tiendas debería vender** para dejar de perder dinero y reinvertir esos recursos en las operaciones más rentables.

## 3. Conjunto de Datos (Dataset) 💾

El análisis se basa en cuatro conjuntos de datos separados, cada uno correspondiente a una tienda (`tienda_1.csv`, `tienda_2.csv`, `tienda_3.csv`, `tienda_4.csv`). Los datos fueron proporcionados por Alura Latam como parte de un desafío de Data Science.

Cada conjunto de datos contiene información sobre:
* Ventas
* Productos
* Categorías
* Calificaciones de clientes
* Costos de envío

## 4. Análisis Realizado 📊

Para llegar a una conclusión informada, se realizaron las siguientes visualizaciones y análisis comparativos usando Pandas y Matplotlib:

1.  **Ingresos Totales por Tienda:** Un gráfico de barras que compara el rendimiento financiero total, siendo este el factor decisivo.
2.  **Calificación Promedio por Tienda:** Un gráfico de barras horizontal para comparar la satisfacción del cliente en cada tienda.
3.  **Costo de Envío Promedio:** Un gráfico de líneas para identificar qué tienda tiene la logística más favorable para el cliente.
4.  **Ventas por Categoría:** Gráficos de barras para entender qué categorías (ej. Electrónicos, Muebles) son más fuertes en cada local.
5.  **Productos Más y Menos Vendidos:** Un gráfico de barras agrupadas para comparar el producto estrella y el producto con menos rotación de cada tienda, lado a lado.

## 5. Herramientas Utilizadas 🛠️

* **Python**
* **Pandas** (para la manipulación, agrupación y concatenación de datos)
* **Matplotlib** (para toda la generación de gráficos estáticos)
* **Numpy** (para el cálculo de posiciones en gráficos agrupados)
* **Google Colab** (como entorno de desarrollo)

## 6. Conclusión y Recomendación Final 💡

**Recomendación: Vender la Tienda 4.**

El análisis concluyó que, si bien la Tienda 4 presenta métricas operativas positivas (la calificación de cliente más alta y el costo de envío más bajo), su **rendimiento financiero es el más débil del grupo**.

El gráfico de **Ingresos Totales** demuestra claramente que la Tienda 4 genera significativamente menos ingresos que las tiendas 1, 2 y 3. Dado que el objetivo es optimizar el negocio y eliminar la operación menos rentable, la Tienda 4 es la candidata lógica para la venta. Los recursos de su manutención pueden ser reinvertidos en las otras tres tiendas para potenciar su ya superior rendimiento.
