**Título y descripción del proyecto**
# telecom-analysis


**Objetivos**
Este repositorio contiene el análisis realizado durante el Sprint 7 del caso ConnectaTel, para identificar segmentos de la poblacion que utilizan como medio de comunicacion la empresa de ConnectaTel


**Datasets utilizados**
El dataset `plans` incluye unicamente 2 filas y 8 columnas
El dataset `users` incluye 4,000 filas y 8 columnas
El dataset `usage` incluye 40,000  filas y 6 columnas

En las cueles se encuentra distribuida la informacion de los clientes, contiene valores faltantes, sentinels, outliers y problemas de calidad 

**Metodología y etapas**
-Exploración de la estructura de los datasets
-Identificación de problemas de calidad de datos
-Detección de valores inválidos y sentinels
-Revisión y estandarización de fechas
-Limpieza básica de datos
-Summary statistics de uso por usuario
-Resumen estadístico por usuario durante el 2024
-Visualización de distribuciones (uso y clientes) y outliers
-Identificación de Outliers
-Segmentación de Clientes por edad y uso
-Visualización de la Segmentación de Clientes
-Insight Ejecutivo para Stakeholders

**Tecnologías utilizadas**
-pandas
-seaborn
-matplotlib.pyplot
-numpy

**Cómo ejecutar el proyecto**
1. Abre `notebooks/telecom-analysis.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

**Resultados principales**

Segmentos por Edad
-Se obcerva que el grupo con mayor actividades de servicio para ConnetcaTel es el de Adultos menores a 60 años con una proporcion del 50%
-El segmento con menores servicios utilizados es el de Adultos Mayores, con el 19%**

Segmentos por Nivel de Uso
-Para el analisis usuarios con menos de 5 llamadas y 5 mensajes se les asigno un segmento como de Bajo uso.
-Para usuarios con 10 o mas mensjaes y lalamdas, se consideraron como Uso Alto.


**Conclusiones y recomendaciones**

-Diseñar un plan exclusivo para minutos de llamdas muy prolongados, para algun segmento especial en un plan adecuado.

-Insentivar a los jovenes menores de 30 años al uso de llamdas y mensajes, ya que seguramente su principal medio de comunicacion son las redes socialesciones y outliers


