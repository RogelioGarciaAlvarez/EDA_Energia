# EDA
Análisis de Datos Exploratorio sobre la demanda eléctrica, generación por tipo, precios y condiciones climáticas en España entre 2015 y 2018

Objetivos principales:
1. Análisis del mix energético
2. Análisis de la influencia de factores climáticos en la generación de energía renovable
3. Análisis de la variación del precio de la energía según el método de generación

La información ha sido obtenida de *kaggle*, concretamente se puede acceder a los datasets al sitio través del siguiente [enlace](https://www.kaggle.com/datasets/nicholasjhana/energy-consumption-generation-prices-and-weather/data)

El estudio se realiza sobre dos datasets ubicados en el directorio <data>:
* energy_dataset.csv (35.064 filas y 29 columnas)
* weather_features.csv (178.396 filas y 17 columnas)

Breve descripción de las columnas de cada dataset:

1. energy_dataset.csv
* time: fecha y hora localizada en CET
* generation biomass: energía generada con biomasa en MW
* generation fossil brown coal/lignite: energía generada con X en MW
* generation fossil coal-derived gas: energía generada con X en MW
* generation fossil gas: energía generada con X en MW
* generation fossil hard coal: energía generada con X en MW
* generation fossil oil: energía generada con X en MW
* generation fossil oil shale: energía generada con X en MW
* generation fossil peat: energía generada con X en MW
* generation geothermal: energía geotérmica generada en MW
* generation hydro pumped storage aggregated: energía generada con X en MW
* generation hydro pumped storage consumption: energía generada por reserva hídrica bombeada en MW
* generation hydro run-of-river and poundage: energía generada por escorrentía y bombeo generada en MW
* generation hydro water reservoir: energía generada por reserva hídrica generada en MW
* generation marine: energía mareomotriz generada en MW
* generation nuclear: energía nuclear generada en MW
* generation other: energía generada con otros medios en MW
* generation other renewable: energía renovable generada con otros medios en MW
* generation solar: energía solar generada en MW
* generation waste: energía generada a partir de residuos en MW
* generation wind offshore: energía eólica (mar) generada en MW
* generation wind onshore: energía eólica (tierra firme) generada en MW
* forecast solar day ahead: previsión de energía solar generada en MW
* forecast wind offshore day ahead: previsión de energía eólica (mar) generada en MW
* forecast wind onshore day ahead: previsión de energía eólica (tierra firme) generada en MW
* total load forecast: prevision de demanda de energía
* total load actual: demanda de energía
* price day ahead: precio del dia anterior en EUR/MWh
* price actual: precio en EUR/MWh

2. wather_features.csv
* dt_iso: fecha y hora localizada en CET
* city_name: nombre de la ciudad
* temp: temperatura en K
* temp_min: temperatura mínima en K
* temp_max: temperatura máxima en K
* pressure: presión atmosférica en hPa
* humidity: porcentaje de humedad
* wind_speed: velocidad del viento en m/s
* wind_deg: dirección del viento en grados (0: Norte, 90: Este, 180: Sur, 270: Oeste)
* rain_1h: precipitación de lluvia acumulada en la hora anterior