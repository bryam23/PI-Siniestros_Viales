#                                                       PROYECTO INDIVIDUAL: SINIESTROS VIALES


# Contexto

El objetivo de este proyecto es examinar y enfrentar los problemas relacionados con los accidentes de tráfico en Buenos Aires. Utilizando la información suministrada por el Observatorio de Movilidad y Seguridad Vial de la Secretaría de Transporte de la Ciudad Autónoma de Buenos Aires, buscamos entender los incidentes viales, descubrir patrones, sugerir estrategias preventivas y evaluar el impacto de las medidas tomadas.



# Rol a desarrollar

En este proyecto, se nos presenta el desafío de asumir el papel de un Analista de Datos y llevar a cabo un análisis exhaustivo de los datos relacionados con la mortalidad en accidentes de tráfico en la ciudad de Buenos Aires. Nuestra tarea implica analizar y presentar la información de manera que se puedan identificar tendencias y tomar decisiones informadas sobre las medidas preventivas que podrían implementarse en el futuro para reducir los accidentes y las pérdidas de vidas debido a esta causa.



# (ETL) Extraccion, Transformacion y Carga

En un primer paso, abordamos el archivo homicidios.xslx realizando un proceso de Extracción, Transformación y Carga (ETL). Extraímos y organizamos la información de ambas pestañas en dataframes separados. Luego, revisamos y manejamos los datos nulos, identificamos duplicados, elegimos y unificamos tipos de datos, y eliminamos algunas columnas. Realizamos transformaciones para abordar los vacíos existentes y dejar la data en las mejores condiciones para el análisis exploratorio (EDA) y la presentación en el Dashboard. Finalmente, combinamos ambos dataframes en uno completo, que exportamos en formato CSV. Todo el proceso está detallado y documentado en el archivo [ETL.ipynb](ETL.ipynb)

Además, empleamos web scraping para obtener datos históricos de la población de Buenos Aires desde Wikipedia, con el propósito de analizar la variabilidad en la población y correlacionarla con las tasas de accidentes en el periodo de 2016 a 2021, aqui pueden encontrar todo el procedimiento que llevamos acabo con web scraping:[Web_Scraping.ipynb](Web_Scraping.ipynb) "



