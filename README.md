## Nota
El archivo `retail.db` no se incluye en el repositorio porque es generado localmente a partir del dataset original.
Para recrearlo, ejecuta:

```bash
python src/create_database.py

Descripción del proyecto

Este proyecto analiza datos de ventas de un e-commerce utilizando SQL (SQLite) y Python para extraer insights de negocio relevantes.

El objetivo principal es demostrar habilidades en:

Manipulación de datos
Análisis con SQL
Visualización con Python
Pensamiento orientado a negocio

Descripción del proyecto

Este proyecto analiza datos de ventas de un e-commerce utilizando SQL (SQLite) y Python para extraer insights de negocio relevantes.

El objetivo principal es demostrar habilidades en:

Manipulación de datos
Análisis con SQL
Visualización con Python
Pensamiento orientado a negocio

Tecnologías utilizadas
Python (pandas, matplotlib)
SQL (SQLite)
Jupyter Notebook

Se utilizó el dataset Online Retail II, que contiene transacciones reales de un e-commerce.

Incluye información como:

Productos
Cantidades
Precios
Clientes
País
Fechas de compra

impieza de datos

Durante el proceso se realizaron las siguientes transformaciones:

Eliminación de filas vacías
Conversión de tipos de datos (fechas y numéricos)
Eliminación de valores inválidos (cantidades y precios negativos)
Creación de la variable TotalSales

Además, se identificaron registros que no corresponden a productos reales (ej. Manual, DOTCOM POSTAGE), los cuales fueron excluidos del análisis.

Análisis realizado
1. Ventas totales

Se calculó el ingreso total generado por el negocio.

2. Top productos por ingresos

Se identificaron los productos con mayor contribución al revenue.

Insight:
Los productos de decoración del hogar representan una parte importante de los ingresos.

3. Top clientes

Se identificaron los clientes con mayor gasto total.

Insight:
Existe un grupo reducido de clientes que generan un alto porcentaje del revenue (clientes de alto valor).

4. Ventas por país

Se analizó el desempeño del negocio en distintos mercados.

Insight:
El negocio presenta alta concentración en ciertos países, lo que sugiere oportunidades de expansión.

5. Tendencia mensual

Se analizaron las ventas a lo largo del tiempo.

Insight:
Se observan patrones de estacionalidad en el comportamiento de compra.

Conclusiones de negocio:
Los productos de decoración son los principales generadores de ingresos
Existe un grupo de clientes de alto valor que debe ser priorizado
Hay oportunidades de crecimiento en mercados internacionales
La limpieza de datos es clave para obtener insights confiables