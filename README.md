# <h1 align=center> Proyecto de Data Analyst sobre Análisis de Siniestros Viales en la Ciudad de Buenos Aires 2016-2021

![alt text](./img/siniestro-viales-3.jpg)

# <h1 align=center> **PROYECTO INDIVIDUAL Nº2 - DATA ANALITS** </h1>


Análisis de Siniestros Viales en la Ciudad de Buenos Aires

## INTRODUCCIOIN

Las estadísticas elaboradas a partir de los datos de los fallecidos y los lesionados en siniestros viales tienen como objetivo fundamental conocer las características demográficas básicas de las víctimas y de las circunstancias de los eventos, elementos que constituyen un insumo fundamental para instrumentar la prevención e implementar
las mejoras necesarias con el fin de evitar este verdadero flagelo

Las gravísimas consecuenciassociales de las muertes en situación de tránsito, se añaden al alto costo que tiene la pérdida evitable de vidas humanas.


## Descripción del Proyecto

Este proyecto tiene como objetivo realizar un análisis de los siniestros viales en la Ciudad de Buenos Aires, utilizando datos recopilados durante el período 2016-2021 por el Observatorio de Movilidad y Seguridad Vial (OMySV). El análisis se centra en identificar patrones, tendencias y factores de riesgo asociados con los accidentes viales, con el fin de proporcionar información valiosa para la toma de decisiones por parte de las autoridades locales y para la prevención de futuros incidentes.

Segun la página web del censo 2022 del Gobierno Argentino, Ciudad Autónoma de Buenos Aires tiene un total de población 3.121.707 habitantes (Censo 2022), pero tiene la enorme particularidad que, acorde al CONSEJO ECONÓMICO Y SOCIAL DE LA CIUDAD DE BUENOS AIRES aproximadamente 3,5 millones de personas (El doble de la población estable) ingresan diariamente a la Ciudad Autónoma de Buenos Aires (CABA) desde los diversos municipios del Gran Buenos Aires, por lo que hacer un calculo de KPI´s tomando datos del censo serian muy fuera de escalas e inexactos.


## Contenido del Repositorio

data/: Carpeta que contiene los dataset en formato csv, ya limpios con dos hojas de datos: "hechos" y "víctimas", así como diccionarios de datos adicionales para una mejor comprensión de la información.

notebooks/: Carpeta que contiene los notebook de Jupyter con el ETL del archico original en formato xslx y el análisis exploratorio de datos (EDA) realizado.

dashboards generado durante el análisis.

## Tecnologias y herramientas utilizadas

Para el desarrollo del EDA (*Exploratory Data Analysis*), se utilizaron las siguientes herramientas y tecnologias:


![VSCode](https://img.shields.io/badge/-VSCode-333333?style=flat&logo=visual-studio-code)
![Python](https://img.shields.io/badge/-Python-333333?style=flat&logo=python)
![Jupyter](https://img.shields.io/badge/-Jupyter-333333?style=flat&logo=jupyter)
![Pandas](https://img.shields.io/badge/-Pandas-333333?style=flat&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-333333?style=flat&logo=WordCloud)
![Seaborn](https://img.shields.io/badge/Seaborn-333333?style=flat&logo=Seaborn)

Para el desarrollo del dashboard, se utilizaron las siguientes herramientas:

![PowerBI](https://img.shields.io/badge/PowerBI-333333?style=flat&logo=powerbi)
![DAX](https://img.shields.io/badge/DAX-333333?style=flat&logo=DAX)



## Reporte del Análisis
Se trabajo sobre el archivo homicidios.xlsx al cual se le realizo el proceso de ETL (extract, Tranform and Load) y de EDA (Exploratory Data Analysis).

En el ETL realizado en el notebook ETL.ipynb, se examinaro, limpiaron y confiabilizaron los diferentes aspectos de los datos, como la presencia de valores faltantes, outliers y duplicados.

El análisis exploratorio de datos (EDA) realizado se encuentra documentado en el notebook EDA.ipynb en la carpeta notebooks/. así como también se presentan gráficos y conclusiones relevantes obtenidas durante el análisis.

KPIs Propuestos
1. Reducción de la Tasa de Homicidios en Siniestros Viales
Se propone reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en comparación con la tasa del semestre anterior. La fórmula para calcular la tasa de homicidios en siniestros viales es: (Número de homicidios en siniestros viales / Población total) * 100,000.

2. Reducción de Accidentes Mortales de Motociclistas
Se propone reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en comparación con el año anterior.



## Recomendaciones al Gobierno de la Ciudad:

![alt text](./img/peaton_descuidado.jpg)

Algunas propuestas para mejorar el tránsito y la Seguridad Vial, son simples, sencillas, realizables en forma inmediata la mayoría de ellas, con efectos de muy rapido impacto en la sociedad y de probada eficacia internacional:

* Implementar campañas de concientización sobre seguridad vial.

* Controlar prioritariamente el respeto absoluto por el semáforo en rojo y la prioridad peatonal.

* Impedir en forma efectiva el estacionamiento en las avenidas y calles de mayor tránsito, en ambas manos, máxime cuando lo es en doble o triple fila.

* Fortalecer los controles vehiculares y aplicar sanciones más severas para las infracciones.

* Mejorar la infraestructura vial, incluyendo señalización, mantenimiento y diseño adecuado.

* Priorizar la seguridad de los grupos más vulnerables: motociclistas, peatones y jóvenes conductores.

* Implementar medidas específicas en las zonas y horarios de mayor riesgo.


### Es importante destacar que la seguridad vial es una responsabilidad compartida entre todos los actores del sistema de tránsito: conductores, peatones, ciclistas y autoridades. Solo mediante un esfuerzo conjunto y sostenido podremos reducir la cantidad de siniestros viales con víctimas fatales.
