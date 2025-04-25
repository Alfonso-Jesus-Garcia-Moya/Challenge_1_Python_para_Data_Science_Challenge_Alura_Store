# Practicando Python para Data Science: Challenge Alura Store


Este repositorio contiene la resolución del Challenge Alura Store, cuyo objetivo es ayudar al Sr. Juan a decidir cuál de sus tiendas vender para poder emprender un nuevo negocio.

A través de herramientas de análisis de datos y visualización en Python, se evalúan métricas clave de rendimiento para identificar la tienda menos eficiente de entre las 4 sucursales de Alura Store.

## Objetivo del proyecto
Analizar datos reales de ventas, rendimiento y reseñas de las tiendas de Alura Store para ofrecer una recomendación basada en evidencia sobre cuál tienda debería vender el Sr. Juan. El análisis considera variables como ingresos, productos más vendidos, satisfacción de los clientes y eficiencia logística.

## Habilidades desarrolladas
Durante este proyecto se practicaron y fortalecieron los siguientes conocimientos:

-Carga y manipulación de archivos .csv utilizando pandas.

-Análisis exploratorio de datos (EDA).

-Visualización de datos con matplotlib.

-Cálculo e interpretación de métricas de negocio: ingresos, ticket promedio, productos más vendidos, categorías dominantes, envío promedio, reseñas promedio.

-Toma de decisiones basadas en datos (data-driven decision-making).

## Requisitos del análisis
Análisis de datos de las tiendas:

Ingresos totales y por categoría.

Productos más vendidos.

Reseñas promedio por tienda.

Tiempo promedio de envío.

Visualización de datos:

Se utilizaron al menos 3 tipos de gráficos diferentes:

-Gráfico de barras.

-Gráfico circular.

-Gráfico de dispersión (scatter plot).

Recomendación final:

Redacción de un informe con una recomendación clara y justificada sobre cuál tienda vender, basada en el análisis cuantitativo.

-Resultados y gráficos
A lo largo del notebook se presentan visualizaciones como:

Comparación de ingresos entre tiendas.

Proporción de reseñas positivas vs negativas.

Tiempo promedio de entrega por tienda.

Ranking de productos más vendidos por tienda.




INFORME FINAL
📊 Informe Final de Análisis para el Señor Juan Autor: Alfonso Jesús García Moya, Data Scientist Fecha: Abril 2025

🔹 Introducción Este informe tiene como finalidad asesorar al Señor Juan en su decisión sobre qué tienda debería vender, considerando un análisis profundo basado en múltiples métricas de desempeño.

Para ello, se utilizaron cuatro bases de datos en formato CSV correspondientes a las siguientes tiendas: tienda, tienda2, tienda3 y tienda4. Los datos fueron provistos desde las siguientes fuentes:

tienda: tienda_1.csv
tienda2: tienda_2.csv
tienda3: tienda_3.csv
tienda4: tienda_4.csv
Las bases de datos contienen información detallada sobre los productos, categorías, precios, costos de envío, fecha de compra, vendedor, lugar de compra, calificación, método de pago, número de cuotas, latitud y longitud. El análisis fue realizado con Python 3 sobre una máquina virtual proporcionada por Google Colaboratory, utilizando un entorno Jupyter Notebook.

🔹 Desarrollo del Análisis

Ingresos Totales por Tienda Se calculó la facturación total por tienda mediante la suma de los precios de todos los productos vendidos. Se obtuvo que:
La tienda con mayor facturación fue tienda con $1,150,880,400.

La tienda con menor facturación fue tienda4 con $1,038,375,700.

Este resultado se representa visualmente en el gráfico grafico_facturacion_por_tienda.

Categorías de Productos Más y Menos Vendidas Se analizó la cantidad unitaria de ventas por categoría. A través del gráfico ***grafico_de_ventas_por_categoria_por_tienda ***se evidenció que:
La categoría más vendida en general fue Muebles, donde tienda3 lidera.
La categoría menos vendida fue Artículos para el hogar, con tienda2 como la tienda con menos volumen.
tienda4 destacó como la que más vendió artículos para el hogar, superando a tienda por solo 30 unidades.
Calificaciones Promedio por Tienda Se calculó la calificación promedio de los clientes para cada tienda (escala del 1 al 5). Como se observa en el gráfico grafico_de_tendencia_de_calificacion_por_tienda:
La tienda mejor calificada fue tienda3 con un promedio de 4.05.
La tienda con peor percepción del público fue tienda con 3.98, seguida de cerca por tienda4 con 4.00.
Productos Más y Menos Vendidos A través del gráfico grafico_de_productos_vendidos_por_tienda, se identificaron los 5 productos más vendidos y los 5 menos vendidos en cada tienda:
tienda: Dominan los productos de la categoría Muebles.
tienda2: Se destacan Electrónicos y Electrodomésticos.
tienda3: Similar a tienda, tiene fuerza en Muebles y Artículos del Hogar.
tienda4: Su top de productos es demasiado variable, lo que indica falta de un nicho definido.
Costo Promedio de Envío por Tienda Se analizó el costo promedio de envío por tienda:
El costo más alto fue el de tienda con $26,018.61.

El costo más bajo fue el de tienda4 con $23,459.00.

Este dato se visualizó en el gráfico grafico_costo_promedio_envio_por_tienda.

🔹 Discusión A pesar de que todas las tiendas presentan fortalezas, también tienen debilidades importantes:

tienda tiene el mayor volumen de ingresos, pero también el costo de envío más alto y la calificación más baja.
tienda2 está mejor definida en su nicho (electrónica), pero su rendimiento en categorías de baja rotación como artículos para el hogar es débil.
tienda3 combina buena facturación, excelente calificación y un nicho claro. Es la opción más balanceada.
tienda4 presenta múltiples debilidades:
Menor facturación
Segunda peor calificación
Costo de envío bajo (único punto fuerte)
Nicho de mercado poco claro
Esto implica un mayor costo en investigación, marketing y posicionamiento de marca, además de baja liquidez por menor facturación.

🔹 Conclusión Con base en el análisis exhaustivo de datos y visualizaciones mencionadas, el equipo de análisis recomienda que el Señor Juan venda la tienda tienda4. Esta tienda, a pesar de tener el menor costo de envío, presenta:

Menor volumen de ventas (por lo tanto, menor cash flow),
Falta de definición clara en su mercado objetivo,
Bajo posicionamiento en percepción del cliente.
Mantener esta tienda implicaría mayores gastos de marketing y análisis de mercado para alcanzar el mismo nivel competitivo que las demás. Venderla permitiría al Señor Juan concentrar esfuerzos y recursos en las tiendas con mayor retorno potencial.
