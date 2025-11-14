🚕 Taxi Data Analysis – Python & SQL

📌 Descripción

Este proyecto combina consultas SQL con análisis exploratorio en Python para estudiar la actividad de taxis en Chicago.
A partir de varios datasets, se analizan patrones de viajes por compañía, barrios con mayor número de finalizaciones y se realiza una prueba de hipótesis relacionada con la duración de viajes en condiciones climáticas específicas.

🎯 Objetivos del análisis
1. Exploratory Data Analysis (EDA) – Python

Usando dos datasets:

project_sql_result_01.csv:

company_name: compañía de taxis

trips_amount: número de viajes (15–16 noviembre 2017)

project_sql_result_04.csv:

dropoff_location_name: barrios donde terminaron los viajes

average_trips: promedio de viajes finalizados en noviembre de 2017

Se realizaron las siguientes tareas:

Importar y explorar los datos

Verificar tipos de datos

Identificar los Top 10 barrios con más viajes

Crear visualizaciones:

Viajes por empresa de taxis

Top 10 barrios con mayor número de finalizaciones

Redactar conclusiones basadas en los gráficos

2. Prueba de hipótesis – Python

Dataset:

project_sql_result_07.csv

start_ts: fecha y hora del viaje

weather_conditions: clima al inicio del viaje

duration_seconds: duración del viaje

Hipótesis evaluada:

“La duración promedio de los viajes desde el Loop al Aeropuerto O'Hare cambia los sábados lluviosos.”

Incluye:

Definición de hipótesis nula y alternativa

Elección del nivel de significación (alfa)

Prueba estadística utilizada (y justificación)

Interpretación del resultado final

🛠 Tecnologías utilizadas

Python (Pandas, NumPy, SciPy)

Matplotlib / Seaborn

SQL

Jupyter Notebook


📝 Resultados principales


Top 10 Compañías con mayor número de viajes:
1  Flash Cab        
2  Taxi Affiliation Services         
3  Medallion Leasing         
4  Yellow Cab          
5  Taxi Affiliation Service Yellow          
6  Chicago Carriage Cab Corp          
7  City Service          
8  Sun Taxi          
9  Star North Management LLC          
10  Blue Ribbon Taxi Association Inc.          

Top 10 barrios por finalizaciones de viaje: 
1  Loop  
2  River North  
3  Streeterville    
4  West Loop   
5  O'Hare   
6  Lake View    
7  Grant Park   
8  Museum Campus   
9  Gold Coast  
10  Sheffield & DePaul

Resultado de la prueba de hipótesis:

Hipotesis: "La duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O'Hare cambia los sábados lluviosos"

Dado que los datos provistos no tienen registros de las condiciones climaticas los dias sabados, se propone una nueva hipotesis: 

"¿La duración promedio de los viajes cambia dependiendo de si las condiciones climáticas son “Good” o “Bad”?"

Conclusión: La duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O’Hare cambia cuando llueve.

🙋‍♀️ Autora

Jhoanny Alcocer Solano — Data Analyst Jr
