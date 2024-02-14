#                                                       PROYECTO INDIVIDUAL: SINIESTROS VIALES


## Introduccion

El objetivo de este proyecto es examinar y enfrentar los problemas relacionados con los accidentes de tráfico en Buenos Aires. Utilizando la información suministrada por el Observatorio de Movilidad y Seguridad Vial de la Secretaría de Transporte de la Ciudad Autónoma de Buenos Aires, buscamos entender los incidentes viales, descubrir patrones, sugerir estrategias preventivas y evaluar el impacto de las medidas tomadas.



# Rol a desarrollar

En este proyecto, se nos presenta el desafío de asumir el papel de un Analista de Datos y llevar a cabo un análisis exhaustivo de los datos relacionados con la mortalidad en accidentes de tráfico en la ciudad de Buenos Aires. Nuestra tarea implica analizar y presentar la información de manera que se puedan identificar tendencias y tomar decisiones informadas sobre las medidas preventivas que podrían implementarse en el futuro para reducir los accidentes y las pérdidas de vidas debido a esta causa.



# (ETL) Extraccion, Transformacion y Carga

En el notebook [text](ETL.ipynb), se llevo a cabo todo el proceso de ETL utilizando bibliotecas como Numpy, Pandas, BeautifulSoup y Requests en Python. Extrajimos datos de ambas hojas de un libro de Excel, realizamos diversas transformaciones como eliminar columnas redundantes, normalizar tipos de datos y fusionar dataframes. Abordamos la gestión de valores nulos, reemplazando 'SD' con etiquetas más descriptivas y, en algunos casos, imputando valores basados en estadísticas como la media de edades presentes en el conjunto de datos. 

Además, empleamos web scraping para obtener datos históricos de la población de Buenos Aires desde Wikipedia, con el propósito de analizar la variabilidad en la población y correlacionarla con las tasas de accidentes en el periodo de 2016 a 2021, aqui pueden encontrar todo el procedimiento que llevamos acabo con web scraping:[text](Web_Scraping.ipynb) "