Aplicando el procedimiento de la prueba de Dickey Fuller a series de tiempo no estacionarias
=================

### Autores

| Autor                 | Origen                               |
| --------------------- | ------------------------------------ |
| Emmanuel Gutiérrez    | Universidad del Norte                |
| Alvin Henao           | Universidad del Norte                |


El artículo original del que nos basamos en este estudio lo puedes descargar en el siguiente link. [Descarga aquí](ANALYSIS_OF_COVID_19_DATA_USING_ARIMA_TIME_SERIES_MODEL.pdf)

Los autores del artículo orginal son: 

| Autor                 | Origen                               |
| --------------------- | ------------------------------------ |
| Başak Er              | Dokuz Eylul University               |
| Murat Emeç            | Marmara University                   |
| Mehmet Hilal Ozcanhan | Dokuz Eylul University               |

### Resumen

El covid-19 provocó una pandemia que afectó en escala global al mundo desde diciembre de 2019. A nivel mundial, la investigación se ha centrado en cuestiones como la detección, prevención, mitigación y predicción de sus causas y consecuencias. Se han realizado diversos estudios limitados a zonas geográficas, países o situaciones específicas, así como modelizaciones globales. Los modelos creados en los estudios fueron capaces de proporcionar información sobre el progreso de la pandemia y los resultados a los que conducirá (Benvenuto, 2020). La visión analítica obtenida permitió a los gobiernos tomar decisiones más precisas y hacer planes para el futuro (Fang Y. N., 2020). El conocimiento previo de las próximas cifras de infecciones también ayudó a controlar la ansiedad, sobre la pandemia. Este estudio proporciona un análisis de la propagación del COVID-19 en cinco países, durante un periodo de cinco meses, de marzo a julio de 2020. El análisis muestra una tendencia similar para todo el mundo. Los países que pueden asociarse con la región geográfica y las similitudes de población se estudiaron utilizando el modelo de series temporales de media móvil autorregresiva (ARIMA). Los resultados del análisis del modelo ARIMA mostraron que el modelo resultaba preciso para las previsiones a corto plazo, mientras que las previsiones mensuales o anuales presentaban grandes errores. Se observó que el margen de error en el análisis de los casos de COVID-19 basado en los países aumentaba para el largo plazo; hasta un punto en que no se podía hacer una previsión satisfactoria. La actualización frecuente del modelo con nuevos datos dio resultados con errores muy pequeños. Se puede concluir que el modelo ARIMA es capaz de dar cifras precisas de previsión a corto plazo con muy pocos errores, sobre la pandemia COVID-19.

### Estado del estudio

| Estado            | Descripción                          |
| ----------------- | ------------------------------------ |
| <img src="https://img.shields.io/badge/Study%20Status-Design%20Finalized-brightgreen.svg" alt="Study Status: Design Finalized"> | El estudio ha sido finalizado. | 

### Palabras claves

- `Series de Tiempo`
- `Modelos ARIMA`
- `Prueba de Dickey Fuller`
- `Prueba de raíz unitaria`
- `Algoritmo`
- `Time Series`
- `ARIMA Model`
- `Test of Dickey Fuller`
- `Test of Unit Root`
- `Algorithm`

### Tipo de estudio

Identificación de modelo ARIMA para predecir comportamientos de Series de Tiempo

### Data

En esta sección se encuentra la Data necesaria para ejecutar el modelo. 
[Descarga aquí](time_series_covid19_global_JHH.csv)

La información contiene los casos confirmados de COVID-19 y las muertes por COVID-19 para el periodo desde el 12 de marzo de 2020 hasta el 9 de julio de 2020. Esta información se obtuvo del sitio web oficial de la Universidad Johns Hopkins (Universidad, 2020). Una vez se descargó la Data creó una base de datos de series de tiempo utilizando Microsoft Excel, de tal forma que facilitara el uso de la data en el análisis.

El conjunto de datos abarca información de Turquía, Irán, Francia, Alemania e Italia. Contiene un total de 25 columnas y 121 filas. A continuación se presenta una ampliación de la estructura de la data.

|Columna               |Descripción|
| -------------------- | ------------------------------------ |
| ***Fecha:***         |Fecha |
| ***C_Total:***       |# total de casos acumulados a la fecha de los 5 países seleccionados |
| ***CPD_Total:***     |# total de casos por día de los 5 países seleccionados |
| ***C_France:***      |# de casos acumulados a la fecha en Francia |
| ***CPD_France:***    |# de casos por día en Francia |
| ***C_Germany:***     |# de casos acumulados a la fecha en Germany |
| ***CPD_Germany:***   |# de casos por día en Germany |
| ***C_Iran:***	       |# de casos acumulados a la fecha en Iran |
| ***CPD_Iran:***	     |# de casos por día en Iran |
| ***C_Italy:***	     |# de casos acumulados a la fecha en Italy |
| ***CPD_Italy:***     |# de casos por día en Italy |
| ***C_Turkey:***	     |# de casos acumulados a la fecha en Turkey |
| ***CPD_Turkey:***	   |# de casos por día en Turkey |
| ***M_Total:***	     |# total de muertes acumuladas a la fecha de los 5 países seleccionados |
| ***MPD_Total:*** 	   |# total de muertes por día de los 5 países seleccionados |
| ***M_France:***	     |# de muertes acumuladas a la fecha en Francia |
| ***MPD_France:***	   |# de muertes por día en Francia |
| ***M_Germany:***	   |# de muertes acumuladas a la fecha en Germany |
| ***MPD_Germany:***   |# de muertes por día en Germany |	
| ***M_Iran:***	       |# de muertes acumuladas a la fecha en Iran |
| ***MPD_Iran:***	     |# de muertes por día en Iran |
| ***M_Italy:***	     |# de muertes acumuladas a la fecha en Italy |
| ***MPD_Italy:***	   |# de muertes por día en Italy | 
| ***M_Turkey:***	     |# de muertes acumuladas a la fecha en Turkey |
| ***MPD_Turkey:***    |# de muertes por día en Turkey |

### Código fuente - R

En esta sección se encuentra el código fuente en R necesario para poder ver el resultado del análisis realizado. 
[Descarga aquí](AnalisisCovid19_ModeloSeriesTiempo_Arima_Ampliacion.md)
