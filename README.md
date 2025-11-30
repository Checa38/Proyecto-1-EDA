# Proyecto-1-EDA
Primer proyecto del Máster en Data Science &amp; IA de Evolve.

Este proyecto recoge el análisis exploratorio del Maddison Project Dataset 2020, un conjunto de datos histórico con información económica y demográfica de distintos países a lo largo del tiempo. El objetivo principal ha sido entender su estructura, revisar su calidad y dejarlo limpio para poder trabajar con él sin problemas.

Durante el proceso aparecieron varios fallos típicos: valores numéricos guardados como texto, espacios invisibles que impedían convertirlos, códigos de país incompletos y algunos registros directamente incoherentes. Antes de analizar nada fue necesario corregir estos detalles, normalizar las columnas, completar datos faltantes y reorganizar el dataset por país y año para que la serie temporal tuviera sentido.

Una vez todo quedó en buen estado, las primeras visualizaciones mostraron lo que cabía esperar en un dataset así: el PIB per cápita mundial crece de forma sostenida a lo largo de los años y siguen existiendo diferencias enormes entre países, especialmente en el año más reciente. Estas tendencias ayudan a situar el contexto histórico y a entender cómo ha evolucionado la economía global.

El proyecto deja el dataset listo para análisis posteriores, comparaciones entre regiones o cualquier tipo de modelo que se quiera construir encima.