# <center>Proyect  N2 Data Science.</center>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/pXPcKY3s/henry2.png' border='0' alt='henry2'/></a>

# <center> Data Analytics .</center>
<div align="center">
  #  Data Analytics.
</div>
<center><a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/yYShgJ8L/image.png' border='0' alt='image'/></a></center>

------------
# Indice.

------------

- Introducción y Contexto.
- Fuente de los Datos.
- Diccionario de Datos.
- Flujo de trabajo.
- ETL_EDA
- EDA.
- Propuesta de negocio.
- KPI Metricas
- Dashboard .
- Colaboradores.


# Introducción y Contexto.

------------
Las telecomunicaciones desempeñan un papel fundamental en nuestra sociedad actual y su importancia solo continúa creciendo. Estas tecnologías permiten la transmisión de información y la comunicación a larga distancia a través de medios electrónicos como la telefonía, la televisión, la radio y, especialmente, el internet.

En la era digital en la que vivimos, el internet se ha convertido en una parte integral de nuestras vidas. Nos permite acceder a una amplia gama de servicios y recursos en línea, desde comunicarnos con personas de todo el mundo hasta acceder a información instantánea y realizar transacciones comerciales. El internet ha transformado la forma en que trabajamos, aprendemos, nos entretenemos y nos relacionamos.

El futuro de las telecomunicaciones se presenta emocionante y lleno de posibilidades. Con los avances tecnológicos en curso, como la llegada de la tecnología 5G, se espera una mayor velocidad y capacidad de conexión, lo que permitirá una comunicación más rápida y eficiente. Esto abrirá las puertas a nuevas aplicaciones y servicios, como el Internet de las Cosas (IoT), la realidad virtual y aumentada, y la inteligencia artificial.

Además, se espera que las telecomunicaciones desempeñen un papel crucial en la transformación digital de diversos sectores, como la salud, la educación, la industria y el transporte. La telemedicina permitirá la atención médica. En Argentina, las telecomunicaciones han experimentado avances significativos en los últimos años. Según datos disponibles, se registraron un total de 62,12 millones de conexiones en el país en el año 2020. Esto demuestra el crecimiento y la importancia del sector en Argentina.

El Ente Nacional de Comunicaciones (ENACOM) desempeña un papel fundamental en la regulación y supervisión de las telecomunicaciones en Argentina. Esta entidad se encarga de garantizar el acceso equitativo a los servicios de telecomunicaciones, promover la competencia y proteger los derechos de los usuarios.

El análisis del comportamiento del sector de las telecomunicaciones a nivel nacional, basado en datos confiables proporcionados por ENACOM, permite a las empresas prestadoras de servicios tomar decisiones estratégicas informadas. Esto incluye identificar oportunidades de crecimiento, mejorar la calidad de los servicios y adaptarse a las demandas cambiantes de los usuarios. distancia, la educación en línea se volverá más accesible y personalizada, y la industria se beneficiará de la automatización y la conectividad inteligente.

En cuanto a la conectividad, se espera que el acceso a internet se expanda aún más, incluso en áreas rurales y remotas. Los esfuerzos para reducir la brecha digital y garantizar la inclusión digital serán fundamentales para que todas las personas puedan aprovechar los beneficios de las telecomunicaciones.


-------
El analisis en el que nos enfocamos, esta estrechamente relacionado con la comunicación, la conectividad, la conexión de internet tanto  a nivel nacional como por cada una de las provincias. En este contexto podemos afirmar que se hizo un barrido por los distintos servicios disponibles a nivel de  telecomunicaciones como son los servicios de telefonía movil, telefonia fija  y todas las variedades existentes de conexiones a  la red.  
  Por otro lado  se hicieron estudios de los distintos rangos de  velocidades , la velocidad media de bajada, el crecimiento porcentual de estas variaciones existentes en las distintas provincias y la detección de zonas críticas respecto a los rangos obtenidos.
 De manera especifica abordamos aspectos técnicos como lo son el tipo de conexiones por tecnologias especificas(ADSL,cableModem, Fibra Optica,Dial Up, Banda Ancha)

A partir del análisis realizado, he llegado a conclusiones que consideran diferentes perspectivas y oportunidades de mejora en el sector, con el objetivo de crear una propuesta de negocio que se base en mejorar la cobertura y la calidad de los servicios de acceso a Internet, así como en establecer indicadores de rendimiento relacionados con este objetivo. Todos estos hallazgos se presentan en este informe y se detallan más específicamente en el contenido de este repositorio. 


# Fuente de los Datos.


------------
- Para este proyecto, toda la información utilizada en este análisis se obtuvo de los conjuntos de datos disponibles en el sitio oficial del ENACOM (Ente Nacional de Comunicaciones).
- Datos transformados en el ETL_EDA.
- Datos transformados en el EDA.

# Diccionario de Datos.

                    
Campo  | Descripción
------------- | -------------
Banda Ancha Fija |  conexión de internet de alta capacidad que se entrega a través de infraestructura fija
Cable Modem | conexiones de tipo Cablemodem en la provincia para el año y trimestre específicos.
Fibra Óptica|Número de conexiones de tipo Fibra óptica en la provincia para el año y trimestre específicos.
Wireless | Número de conexiones de tipo Wireless en la provincia para el año y trimestre específicos.
Total de Conexiones | Total de conexiones de Internet en la provincia para el año y trimestre específicos.
Acceso para cada 100 hab. | Número de accesos a Internet por cada 100 habitantes en la provincia para el año y trimestre específicos.
Acceso para cada 100 hog. | Número de accesos a Internet por cada 100 hogares en la provincia para el año y trimestre específicos.
latitud| Medida de la distancia al norte o al sur del ecuador para ubicar estudio especifico de las provincias en  Argentina.
longitud | Medida de la distancia al norte o al sur del ecuador para ubicar estudio especifico de las provincias en  Argentina. (visualización geografica)
mapa | Vista del mapa de argentina con información importante.
Hasta 512 kbps|Número de conexiones con velocidad hasta 512 kbps en la provincia para el año y trimestre específicos.
512 Kbps - 1 Mbps | Número de conexiones con velocidad entre 512 Kbps y 1 Mbps en la provincia para el año y trimestre específicos.
1 Mbps - 6 Mbps | Número de conexiones con velocidad entre 512 Kbps y 1 Mbps en la provincia para el año y trimestre específicos.
6 Mbps - 10 Mbps | 	Número de conexiones con velocidad entre 6 Mbps y 10 Mbps en la provincia para el año y trimestre específicos.
10 Mbps - 20 Mbps | Número de conexiones con velocidad entre 10 Mbps y 20 Mbps en la provincia para el año y trimestre específicos. 
20 Mbps - 30 Mbps | 	Número de conexiones con velocidad entre 20 Mbps y 30 Mbps en la provincia para el año y trimestre específicos.
30 Mbps |Número de conexiones con velocidad superior a 30 Mbps en la provincia para el año y trimestre específicos.
Total suma Mbps | Total de la suma de todas las conexiones de Internet por velocidad en la provincia para el año y trimestre específicos.

# Flujo de trabajo.
 
## ETL (Extracción, Transformación y Carga de los datos) -> Notebook: ETL_DA.
- Se descargaron algunos dataset a través de la pagina oficial de ENACOM. Al cabo de cierto  periodo de observación de los datos, pude comprobar que dichas tablas contienen valores inconsistentes en determinadas escalas, esto daba como resultado analisis  distorsionados. Por tal motivo inmediatamente busque otra fuente alternativa de los datos, sin dejar de utilizar la plataforma de ENACOM.  Estos datos  fueron extraidos en formato xlsx. Los cuales si  tenian una mayor calidad del dato.
- Transformación de estos data se de xlsx a csv.
- Cambios de tipo de datos, así como extracción de puntos en variables numéricas.
- Unión de dataframe relacionados, y elección de columnas  para poder hacer determinados MERGE.
- Detección de Nulos e imputados.
- Detección de errores.
- Detección de valores atipicos y ausentes.
- Integridad de los datos.
- Creación de un dataframe para la elaboración de un mapa geografico  interactivo. 

## EDA ( Analisis Exploratorio de los Datos). Notebook: EDA.

En esta etapa me concentre en hacer un barrido para analizar los distintos servicios de telecomunicaciones que tiene  Argentina en todas sus provincias.
 En este particular se hizo un analisis de acceso a cada uno de los servicios como fueron :

### Telefonia Movil.
 observamos que en le periodo desde el 2013 hasta el 2022 el acceso a la telefonía movil se ha mantenido constante a través de los años, inclusive para el inicio del 2013 el promedio de acceso por cada 100 habitantes era de 187 y para el 2022 estaba en 128, podriamos inferir de acuerdo a estos datos que hubo un decrecimiento del 18% entre estos años en estudio.
 
 ### Telefonia Fija: 
 Cuando hacemos los distintos analisis con respecto de la telefonía fija, podemos mencionar una Disminución gradual: La media de acceso a la telefonía fija por cada 100 habitantes ha disminuido a lo largo de los años. En 2014, la media era de 22.50, y en 2022, la media disminuyó a 15.61.

Estabilidad en los últimos años: A partir de 2018, la media de acceso a la telefonía fija por cada 100 habitantes se ha mantenido relativamente estable, con pequeñas variaciones. Esto puede indicar una estabilización en el acceso a este servicio. Las provincias con mejor servicio de telefonia fija son : Buenos Aires, Capital Federal, Santa Fe, Cordoba, Mendoza, mientras las de menor servicio de telefonia fija son : Tierra del fuego, la Rioja, Catamarca, Santa Cruz y Formosa. se Obseva una brecha de casi diez veces entre las 5 primeras y las 5 ultimas provincias, la equidad en telefonia fija es abrumadora. Podemos constatar estas estadisticas dado el estudio realizado por las categorias comerciales, hogares, gobierno, da la misma tendecia, a ecepto por gobierno, donde se refleja que tiene un mayor acceso en las provincias de Entre Ríos, Tucuman, Salta, Rio Negro y Misiones.

Hicimos el estudio de la telefonía fija por cada 100 habitantes por provincias. donde se concluyo que siguen el mismo patron que las anteriores, afirmando que las provincias con mayor penetración son Capital Federal, BUenos Aires, La pampa, Santa Fe y tierra del fuego, y las de menor acceso son : Formosa, Jujuy, Santiago del Estero, Chacho y Misiones.

### servicio de internet:
Cuando hicimos el estudio del mayor acceso a internet por provincia de cada 100 hogares, nos llamo poderosamente la atención sus resultados, ya que dio los siguientes resultados: Capital Federal, Tierra del Fuego, La Pampa, Cordoba y buenos Aires. me Llama poderosamente la atención que la tierra del fuego este en el segundo puesto, ya que su ubicación geografica esta totalmente al sur. Donde la estadistica poblacional es bastante menos al resto de las provincia, sin embargo los habitantes y las empresas han apostado al desarrollo de las telecomunicaciones.

Se hizo un estudio exhaustivo de los distintos tipos de conexiones de internet (ADSL,CableModem, Fibra optica Wireless Dial UP) donde podemos concluir que la tecnologia mas utilizada en el periodo de tiempo desde el 2014 hasta el 2002 es CableModem.Seguida de ADSL y luego Fibra optica, cabe mencionar que esta ultima empiza a tener un incremento considerable, podriamos inferir que para los proximos años el aumento de las telecomunicaciones estará enfocada en la fibra optica. haremos un estudio de un KPI para ver que resultado nos podria dar en un futuro de 4 años.

Analizamos los datos de acceso de internet por cada 100 hogares desde el 2014 hasta el 2022, dado como conclusión: análisis:

En el año 2014, hubo 3541.64 accesos de internet por cada 100 hogares. En el año 2015, este número aumentó a 3763.04 accesos por cada 100 hogares. En el año 2016, el número siguió aumentando a 3829.42 accesos por cada 100 hogares. En el año 2017, se registró un aumento adicional a 4082.47 accesos por cada 100 hogares. En el año 2018, hubo un aumento significativo a 4653.84 accesos por cada 100 hogares. En el año 2019, este número continuó aumentando a 5152.00 accesos por cada 100 hogares. En el año 2020, se registró otro aumento a 5388.54 accesos por cada 100 hogares. En el año 2021, hubo un aumento adicional a 5949.93 accesos por cada 100 hogares. Finalmente, en el año 2022, se registró el número más alto hasta ahora, con 6511.06 accesos por cada 100 hogares. Estos datos muestran una tendencia creciente en el acceso a internet por cada 100 hogares a lo largo de los años. Esto puede indicar un mayor acceso a la tecnología y una mayor conectividad en los hogares.

Se hizo el estudio de penetración bajada de internet por año. Alli pudimos observar que en el inicio del 2014 la velocidad promedio era de 3.85 Mbps y fue aumentando progresivamente hasta llegar a los 60 Mbps. este estudio se hizo a traves de los datos suminstrados por la empresa proveedora de servicios : ENACOM En relación con el analisis anterior, tener un enfoque más detallado de estás provincias, puede ser de interes para proponer una oportunidad de mejorar el acceso a conexiones de internet en estas regiones. Pero haré un analisis más detallado de estás para proponer un KPI realista.

 ## KPI 1.** Incremento en la cantidad de acceso al servicio de internet para un tiempo determinado:** Aumentar en un 2% el acceso al servicio de internet para el próximo trimestre, cada 100 hogares, por provincia. 
 
 Métrica: Aumento en el numero de conexiones totales / cada 100 hogares por provincia.
Meta:

Acceso por cada 100 Hab pe 3 2022  | Acceso por cada 100 Hab pe 4 2022
------------- | -------------
26.37  | 26.72
50.22 |50.35
16.62  | 16.73
11.73 |11.66
25.86  | 26.72
50.22 |16.23

