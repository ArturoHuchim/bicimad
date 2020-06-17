# ANÁLISIS DE PATRONES DEL SISTEMA DE TRANSPORTE PÚBLICO BICIMAD

El siguiente repositorio es sobre el Trabajo de fin de Máster llamado: *ANÁLISIS DE PATRONES DEL SISTEMA DE TRANSPORTE PÚBLICO BICIMAD* el cual tiene como objetivo realizar un análisis sobre el Sistema de Transporte Público de Madrid en específico, las líneas de autobús de EMT y el sistema de bicicletas BiciMAD, con la finalidad de ofrecer recomendaciones sobre qué medio de transporte es el más adecuado para realizar trayectos similares a alguna línea de autobús para con ello, hacer más eficiente el Sistema de Transporte.
Para el desarrollo de este proyecto, se emplean técnicas de procesamiento Big Data debido a que las tecnologías y técnicas convencionales para transformar, modelar y analizar los datos son insuficientes para cubrir las necesidades que este trabajo demanda. 
Al final, el objetivo es realizar un dashboard que se encuentra en el apartado de Tableau: Capítulo 5 donde se presentan los resultados del estudio.

3.	Adquisición de datos
* 3.1.1.1. Transport Busetmad.ipynb
  - 3.1.1.1.1 Infoline(General)
  -	3.1.1.1.2 Line stops
*	3.1.1.2 Transport Bicimad-REPO.ipynb
  *	3.1.1.2.1. List BiciMAD Stations
4.  Proceso de transformación de datos
* 4.1. Estaciones de autobús dentro de BiciMAD.ipynb
  - 4.1.1 Distancia haversine
* 4.2. Zona de Madrid Central.ipynb
  - 4.2.1 Clasificación de estaciones de autobús
  -	4.2.2 Clasificación de estaciones de bicicleta
  -	4.2.3 Clasificación de las líneas que empiecen y terminen dentro de la zona
  -	4.2.4 Clasificación de las líneas que empiecen y terminen cerca de la zona
* 4.3.  Zona de BiciMAD.ipynb
  - 4.3.1 Clasificación de las líneas que empiecen y terminen dentro de la zona
  - 4.3.2 Selección de estaciones de BiciMAD que se encuentran alrededor de las cabeceras de autobuses
* 4.4 Viajes en función de rutas.ipynb
  -	4.4.1 Limpieza de los conjuntos de datos de movimientos
  -	4.4.2 Búsqueda de itinerarios
  -	4.4.3 Análisis de los resultados
  -	4.4.4 Estaciones de BiciMAD extra
* 4.5 Fases de BiciMAD.ipynb
  - 4.5.1 Análisis de las fases
  - 4.5.2 Asignación de estaciones aledañas
* 4.6 Frecuencias de líneas.ipynb
  -	4.6.1 Tipos de día 
  -	4.6.2 Frecuencias de líneas
    *	4.6.2.1 Análisis de una petición
    *	4.6.2.2 Conjunto de peticiones por mes
    *	4.6.2.3 Líneas 361 y 362
    *	4.6.2.4 Análisis de la dirección
    *	4.6.2.5 Asignar frecuencias
    *	4.6.2.6 Días festivos como sábado
    *	4.6.2.7 Agregación de frecuencias
    *	4.6.2.8 Asignar frecuencias a los movimientos en bicicleta
5.  Análisis de los resultados
* 5.1. Rutas por línea
  * 5.1.1 Ocupación de la bicicleta respecto a un autobús
  *	5.1.2 Tipos de usuario
  *	5.1.3 Rango de edades
* 5.2 Rutas por línea en función del tipo de día
  * 5.2.1 Viajes en función de la línea
  * 5.2.2 Tipos de usuario
  * 5.2.3 Rango de edades
* Anexo C
  - AnexoC.ipynb
* Tableau
  - Capítulo 4
    * Capitulo 4.twbx
    * 4.5. Fases BiciMAD.twbx
    * Scripts_Adicionales_Tableau_Capitulo_4.ipynb
  - Capítulo 5
    * Capítulo 5.twbx
    * Scripts_Adicionales_Tableau_Capitulo_5.ipynb
  - Anexo C
    * Anexo C.twb
