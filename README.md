# Proyecto Integrado: Análisis Exploratorio de Datos de Viajes en Taxi en Chicago

## Descripción del Proyecto

En este proyecto, analizamos datos de viajes en taxi en Chicago para identificar patrones y probar hipótesis sobre la duración de los viajes. Trabajamos con dos conjuntos de datos que contienen información sobre el número de viajes realizados por diferentes compañías de taxis y la cantidad promedio de viajes que terminan en varios barrios de Chicago en noviembre de 2017.

### Archivos de Datos

- `/datasets/project_sql_result_01.csv`: Contiene datos sobre el número de viajes realizados por diferentes compañías de taxis.
  - `company_name`: Nombre de la empresa de taxis.
  - `trips_amount`: Número de viajes realizados por la empresa el 15 y 16 de noviembre de 2017.

- `/datasets/project_sql_result_04.csv`: Contiene datos sobre los barrios de Chicago donde finalizaron los viajes.
  - `dropoff_location_name`: Barrios de Chicago donde finalizaron los viajes.
  - `average_trips`: Promedio de viajes que terminaron en cada barrio en noviembre de 2017.

- `/datasets/project_sql_result_07.csv`: Contiene datos sobre viajes desde el Loop hasta el Aeropuerto Internacional O'Hare.
  - `start_ts`: Fecha y hora de la recogida.
  - `weather_conditions`: Condiciones climáticas en el momento en que comenzó el viaje.
  - `duration_seconds`: Duración del viaje en segundos.

## Pasos Realizados en el Proyecto

### Paso 1: Importar los Archivos y Estudiar los Datos

- Cargamos los archivos CSV en dataframes de pandas.
- Revisamos la estructura y contenido de los datos para asegurarnos de que los tipos de datos sean correctos.

### Paso 2: Identificar los 10 Principales Barrios en Términos de Finalización del Recorrido

- Analizamos los datos para identificar los 10 barrios con el mayor número de finalizaciones de viajes.
- Creamos gráficos para visualizar:
  - Las empresas de taxis y el número de viajes.
  - Los 10 barrios principales por número de finalizaciones.

### Paso 3: Análisis Exploratorio de Datos

- Generamos gráficos y visualizaciones para entender mejor la distribución y patrones de los datos.
- Sacamos conclusiones basadas en los gráficos y explicamos los resultados obtenidos.

### Paso 4: Prueba de Hipótesis

- Formulamos y probamos la siguiente hipótesis:
  - Hipótesis: "La duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O'Hare cambia los sábados lluviosos."
- Establecimos el nivel de significación (alfa) y planteamos las hipótesis nula y alternativa.
- Utilizamos el criterio adecuado para probar las hipótesis y explicamos el proceso y los resultados.

### Resultados y Conclusión

- Los resultados mostraron que la duración promedio de los viajes difiere significativamente en los sábados lluviosos en comparación con los sábados sin lluvia.
- Este hallazgo sugiere que el mal tiempo tiene un impacto notable en la duración de los viajes, lo que es importante para la planificación y gestión de flotas de taxis.

## Conclusiones del Análisis

- **Distribución de Viajes por Compañía de Taxis**: Se identificaron las principales compañías de taxis en términos de número de viajes.
- **Barrios con Mayor Finalización de Viajes**: Se destacaron los 10 barrios principales en términos de finalización de viajes.
- **Impacto del Clima en la Duración de los Viajes**: Se encontró una correlación entre las condiciones climáticas y la duración de los viajes desde el Loop hasta el Aeropuerto Internacional O'Hare.

## Contribución

Si deseas contribuir a este proyecto, realiza un fork del repositorio y crea una pull request con tus mejoras. Asegúrate de que tu código sigue los lineamientos del proyecto y está bien comentado.

## Licencia

Este proyecto está bajo la licencia MIT. Para más detalles, consulta el archivo LICENSE.
