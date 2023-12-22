# EDA
Análisis de Datos Exploratorio sobre la generación de energía eléctrica y condiciones metereológicas en España

## Objetivos
1. Análisis y evolución del mix energético en España
2. Análisis de la influencia de factores climáticos en la generación de energía renovable

## Fuentes
Los datos de generación de energía y potencia instalada se han obtenido del sitio web de [**red eléctrica**](https://www.ree.es/es/datos/generacion)

Los datos de demanda de energía se han obtenido del sitio web de [**red eléctrica**](https://www.ree.es/es/datos/demanda)

Los datos climatológicos se han obtenido del sitio web de [**X**]()

## Datos
El estudio se realiza sobre X datasets ubicados en el directorio *data* del repositorio:
* estructura_generacion.csv (3.621 filas y 17 columnas)
* demanda.csv (119 filas y 2 columnas)
* potencia_renovables.csv (107 filas y 8 columnas)

Breve descripción de las columnas de cada dataset:

1. estructura_generacion.csv
* Fecha: fecha de generación de la energía
* Hidraulica: energía hidráulica diaria generada en GWh
* Turbinacion bombeo: energía hidráulica por bombeo diaria generada en GWh
* Nuclear: energía nuclear diaria generada en GWh
* Carbon: energía diaria generada con uso de carbón en GWh
* Motores diesel: energía diaria generada con uso de motores diesel en GWh
* Turbina de gas: energía diaria generada con uso de turbinas de gas en GWh
* Turbina de vapor: energía diaria generada con uso de turbinas de vapor en GWh
* Ciclo combinado: energía diaria generada con uso de ciclos combinados en GWh
* Eolica: energía eolica diaria generada en GWh
* Solar fotovoltaica: energía solar fotovoltaica diaria generada en GWh
* Solar termica: energía solar termica diaria generada en GWh
* Otras renovables: energía diaria generada con otras fuentes renovables en GWh
* Cogeneracion: energía diaria generada con uso de cogeneración en GWh
* Residuos no renovables: energía diaria generada con otra fuentes no renovables en GWh
* Residuos renovables: energía diaria generada con residuos renovables en GWh
* Generacion total: energía diaria total generada en GWh

2. demanda.csv
* Fecha: fecha de demanda de la energía
* Demanda: demanda mensual de energía en GWh

3. potencia_renovables.csv
* Fecha: fecha de medición de la potencia instalada
* Hidráulica: potencia instalada para la generación de energía hidráulica hasta la fecha
* Eólica: potencia instalada para la generación de energía eólica hasta la fecha
* Solar fotovoltaica: potencia instalada para la generación de energía solar fotovoltaica hasta la fecha
* Solar térmica: potencia instalada para la generación de energía solar térmica hasta la fecha
* Otras renovables: potencia instalada para la generación de energía de otras fuentes renovables hasta la fecha
* Residuos renovables: potencia instalada para la generación de energía por residuos renovables hasta la fecha
* Potencia renovable: potencia total instalada para la generación de energía renovable hasta la fecha

