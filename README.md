# EDA
Análisis de Datos Exploratorio sobre la generación de energía eléctrica por tipo, precios y condiciones climáticas en España entre 2015 y 2018

## Objetivos
1. Análisis y evolución del mix energético en España
2. Análisis de la influencia de factores climáticos en la capacidad de generación de energía renovable
3. Análisis de la variación del precio de la energía según el método de generación

## Fuentes
La información ha sido obtenida de *kaggle*, concretamente se puede acceder a los datasets del sitio través del siguiente [enlace](https://www.kaggle.com/datasets/nicholasjhana/energy-consumption-generation-prices-and-weather/data)

Los datos de generación de energía se obtuvieron del portal de transparencia de [**ENTSOE**](https://transparency.entsoe.eu/dashboard/show) (Red Europea de Gestores de Redes de Transporte de Electricidad)

Los precios de la energía se obtuvieron del sitio [**esios red eléctrica**](https://www.esios.ree.es/en/market-and-prices)

Los datos climatológicos se obtuvieron del sitio [**OpenWeather**](https://openweathermap.org/)


## Datos
El estudio se realiza sobre dos datasets ubicados en el directorio *data* del repositorio:
* energy_dataset.csv (35.064 filas y 29 columnas)
* weather_features.csv (178.396 filas y 17 columnas)

Breve descripción de las columnas de cada dataset:

1. energy_dataset.csv
* time: fecha y hora localizada en CET
* generation biomass: capacidad de generación de energía con biomasa en MW
* generation fossil brown coal/lignite: capacidad de generación de energía con lignito en MW
* generation fossil coal-derived gas: capacidad de generación de energía con gas derivado del carbón en MW
* generation fossil gas: capacidad de generación de energía con gas en MW
* generation fossil hard coal: capacidad de generación de energía con antracita en MW
* generation fossil oil: capacidad de generación de energía con petróleo convencional en MW
* generation fossil oil shale: capacidad de generación de energía con petróleo (a partir de lutita bituminosa) en MW
* generation fossil peat: capacidad de generación de energía con turba en MW
* generation geothermal: capacidad de generación de energía geotérmica en MW
* generation hydro pumped storage aggregated:
* generation hydro pumped storage consumption: capacidad de generación de energía por consumo de reserva hídrica bombeada en MW
* generation hydro run-of-river and poundage: capacidad de generación de energía por escorrentía de rios y lagos generada en MW
* generation hydro water reservoir: capacidad de generación de energía por reserva hídrica en embalses en MW
* generation marine: capacidad de generación de energía mareomotriz en MW
* generation nuclear: capacidad de generación de energía nuclear en MW
* generation other: capacidad de generación de energía con otros medios en MW
* generation other renewable: capacidad de generación de energía renovable con otros medios en MW
* generation solar: capacidad de generación de energía solar en MW
* generation waste: capacidad de generación de energía a partir de residuos en MW
* generation wind offshore: capacidad de generación de energía eólica (mar) en MW
* generation wind onshore: capacidad de generación de energía eólica (tierra firme) en MW
* forecast solar day ahead: previsión para el dia siguiente de la capacidad de generación de energía solar en MW
* forecast wind offshore day ahead: previsión para el dia siguiente de la capacidad de generación de energía eólica (mar) en MW
* forecast wind onshore day ahead: previsión para el dia siguiente de la capacidad de generación de energía eólica (tierra firme) en MW
* total load forecast: prevision de consumo de energía en MW
* total load actual: capacidad de consumo de energía en MW
* price day ahead: previsión para el dia siguiente del precio en EUR/MWh
* price actual: precio en EUR/MWh

2. wather_features.csv
* dt_iso: fecha y hora localizada en CET
* city_name: nombre de la ciudad
* temp: temperatura media registrada en la hora anterior en K
* temp_min: temperatura mínima registrada en la hora anterior en K
* temp_max: temperatura máxima registrada en la hora anterior en K
* pressure: presión atmosférica en hPa
* humidity: porcentaje de humedad
* wind_speed: velocidad del viento en m/s
* wind_deg: dirección del viento en grados (0: Norte, 90: Este, 180: Sur, 270: Oeste)
* rain_1h: precipitación de lluvia acumulada en la hora anterior en mm
* rain_3h: precipitación de lluvia acumulada en las tres horas anteriores en mm
* snow_3h: precipitación de nieve acumulada en las tres horas anteriores en mm
* clouds_all: porcentaje de cobertura de las nubes
* weather_id: código para describir el tiempo
* weather_main: breve descripción del tiempo
* weather_description: larga descripción del tiempo
* weather_icon: código para el icono del tiempo del sitio web