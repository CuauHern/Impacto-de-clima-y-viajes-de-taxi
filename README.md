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
  
Realicé prueba de hipótesis sobre el impacto del clima en la frecuencia de viajes.

Para una compañia de taxis es importante conocer como los eventos meteorologicos, el clima, afectan la frecuencia de los viajes que se realizan, identificar estos patrones permiten diseñar estrategias para comtemplar la disponibilidad y longitud de los viajes a realizar.

Conocer estos factores permite identificar las compañias que son mas solicitadas y en que ubicaciones se solicitan, lo cual ayuda a garantizar unidades disponibles para todos los servicios que se soliciten, garantiza ingresos constantes sin dejar a usuarios sin atención.

Herramientas y tipo de proyecto:

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white)
![Jupyter](https://img.shields.io/badge/jupyter-3776AB?style=flat-square&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-3776AB?style=flat-square&logo=Pandas&logoColor=white)
![Numpy](https://img.shields.io/badge/Numpy-3776AB?style=flat-square&logo=Numpy&logoColor=white)
![Scipy](https://img.shields.io/badge/scipy-3776AB?style=flat-square&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=flat-square&logo=Matplotlib&logoColor=white)

![EDA](https://img.shields.io/badge/An%C3%A1lisis%20Exploratorio%20de%20Datos-3776AB)
![Limpieza](https://img.shields.io/badge/Limpieza%20de%20Datos-3776AB)
![Transfomacion](https://img.shields.io/badge/Transformaci%C3%B3n%20de%20Datos-3776AB)
![hipotesis](https://img.shields.io/badge/Pruebas%20de%20hipo%C3%B3tesis-3776AB)

Preguntas clave:
1. ¿Cuales  son las 10 principales compañias solicitadas?
2. ¿Cuales son los 10 principales barrios en terminos de finalización del recorrido? 

Se probó  la hipotesis:

"La duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O'Hare cambia los sábados lluviosos".

# Metodologia:

* Preprocesamiento de datos: Se limpiaron y estandarizaron los datos, eliminando inconsistencias y verificando la ausencia de duplicados y valores faltantes.
* Explorartory Data Analysis (EDA): Se analizaron características de viaje por compañia, y detalles de destinos.
* Se probó la hipotesis: Se definió y probó la hipótesis con un nivel de significancia alfa de 0.05

# Conclusiones y recomendaciones

## Factores climáticos:

Se busco identificar si los días sábados con lluvia el promedio de viaje era diferente
* Se identificaron las empresas preferidas de los usuarios
* Se identificarón los destinos mas comunes.

# Estrategias recomendadas:

* Al resultar la prueba de hipótesis negativa, no hay estrategias recomendadas ya que no hay cambios en los días lluviosos a uno normal.

## Visualizaciones destacadas

1. Distribución de compañias preferidas por los usuarios.

   Se puede apreciar la cantidad de viajes finalizados que han realizado las compañias de taxis, y se ve claramente la preferencia de los clientes.
<img width="492" height="550" alt="image" src="https://github.com/user-attachments/assets/7aa1399b-cd51-429f-82c5-bc45423c3dab" />

2. Distribución de destinos preferidos.

   En este gráfico se puede apreciar los destinos preferidos de los usuarios donde el barrio Loop es el mas visitado.
<img width="494" height="472" alt="image" src="https://github.com/user-attachments/assets/f73034af-ec1a-46c0-b107-6d81e7e8cf6b" />
