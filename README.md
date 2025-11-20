 Divvy Bike-Share Analysis

Autor: Angelica Durango

Este proyecto analiza el comportamiento de los usuarios del sistema de bicicletas Divvy para identificar diferencias entre usuarios members y casual, con el objetivo de proponer estrategias que fomenten la conversión a suscripciones anuales.

El análisis se realizó siguiendo la metodología CRISP-DM, usando Excel para la limpieza de datos y Power BI para la visualización.

Contenido del repositorio

README.md → descripción completa del proyecto

case_study_report.pdf → resumen del caso

screenshots/ → capturas del dataset limpio y del dashboard

Nota: El dataset limpio no se sube directamente debido a su tamaño. En su lugar se incluyen capturas.

 Limpieza de datos (Excel)

El dataset original fue limpiado y transformado en Excel aplicando los siguientes pasos:

Normalización del formato fecha-hora

Eliminación de valores faltantes

Detección y eliminación de outliers (viajes negativos o extremadamente largos)

Limpieza de espacios y texto

Creación de nuevas columnas para el análisis:

ride_length  
ride_length_minutes  
day_of_week  
month  
hour  


Debido al gran tamaño del archivo, no se incluye el Excel completo.
En la carpeta screenshots/ se puede ver una vista previa del dataset limpio.

📊 Visualización (Power BI)

El dashboard desarrollado en Power BI incluye:

Número de viajes por mes

Duración media del viaje

Uso por tipo de bicicleta

Horas pico de uso

Si el archivo .pbix no puede subirse por tamaño, se incluye una versión comprimida en .zip o capturas del dashboard dentro de screenshots/.

🔍 Hallazgos principales

Los usuarios casuales realizan viajes más largos que los miembros.

Los miembros usan la bicicleta principalmente entre semana.

Los usuarios casuales muestran un uso más recreativo, especialmente en fines de semana.

Los miembros realizan más viajes al año y de forma más consistente.

🚀 Recomendaciones

Crear campañas dirigidas a convertir usuarios casuales en miembros.

Enfatizar los beneficios económicos de la suscripción anual.

Implementar promociones estacionales durante meses de mayor uso recreativo.

📄 Resumen del caso

El documento completo del análisis está disponible aquí:

case_study_report.pdf

Incluye:

Objetivo

Metodología

Proceso de limpieza

Resultados

Conclusiones y recomendaciones

🛠 Tecnologías utilizadas

Excel

Power BI

GitHub
