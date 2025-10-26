<h1 align="center">Impacto del clima en viajes de taxi</h1>

Datasets utilizados:

* project_sql_result_01.csv
  Con los datos:

  * company_name: nombre de la empresa de taxis
  * trips_amount: el número de viajes de cada compañía de taxis el 15 y 16 de noviembre de 2017. 

* project_sql_result_04.csv
  Con los datos:

  * dropoff_location_name: barrios de Chicago donde finalizaron los viajes
  * average_trips: el promedio de viajes que terminaron en cada barrio en noviembre de 2017.
 
* project_sql_result_07.csv
  Con los datos:

  * start_ts: fecha y hora de la recogida
  * weather_conditions: condiciones climáticas en el momento en el que comenzó el viaje
  * duration_seconds: duración del viaje en segundos
 
Pasos realizados:

1. Importar los archivos
2. Estudiar los datos que contienen
3. Confirmación de que los tipos de datos sean correctos
4. Identificación de los 10 principales barrios en términos de finalización del recorrido
5. Creación de gráficos: empresas de taxis y número de viajes, los 10 barrios principales por número de finalizaciones
6. Prueba de hipótesis: "La duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O'Hare cambia los sábados lluviosos".

