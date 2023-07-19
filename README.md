# Proyecto_Individual_2-DA_Telecomunicaciones

Desarrollado por : Cristian Suazo Dondero DTS-12

- Contexto

La industria de las telecomunicaciones ha jugado un papel vital en nuestra sociedad, facilitando la información a escala internacional y permitiendo la comunicación continua incluso en medio de una pandemia mundial. La transferencia de datos y comunicación se realiza en su mayoría a través de internet, líneas telefónicas fijas, telefonía móvil, casi en cualquier lugar del mundo.

En comparación con la media mundial, Argentina está a la vanguardia del desarrollo de las telecomunicaciones, teniendo para el 2020 un total de 62,12 millones conexiones.

En este contexto, una empresa prestadora de servicios de telecomunicaciones desea reconocer el comportamiento de este sector a nivel nacional. La principal actividad de la empresa es brindar acceso a internet, pero también es importante considerar el resto de los servicios.

- Análisis

Una empresa de telecomunicaciones desea saber cómo es el contexto en telecomunicaciones en Argentina. Es muy probable que tenga fines comerciales para poder invertir. Dentro de los indicadores que se definieron para su análisis son: 
1) Tener un entendimiento de todo el contexto de telecomunicaciones en general. 
2) Tener un mayor detalle de la parte de conexión a internet.

Se definieron dos indicadores principales: 
1) El nivel de penetracion por cada 100 hogares. 
2) Los ingresos trimestrales y anuales.
De esa forma la empresa podrá analizar las necesidades de tomas de desiciones de manera mas segura.

Según un análisis temporal, se muestra una tendencia creciente en el nivel de ingresos en las tecnologías de internet fijo, telefonía móvil, y TV, observándose una tendencia más alta de crecimiento de Internet. Asimismo, la telefonía móvil muestra una variación menos predecible mostrandose picos de subida y bajada a lo largo de los años.

La calidad de servicio de internet a lo largo de los años ha ido aumentando, pues la velocidad de internet ha tenido un cambio significativo de Mpbs desde el año 2018.

KPIs

En base a la información proporcionada se puede definir los siguientes indicadores de análisis descriptivo. Para ello, se debe tener en cuenta que se desea mostrar un panorama general del estado de las comunicaciones en el tiempo, y geográficamente cómo se encuentra el nivel de penetración, para luego hacer un análisis más detallado del nivel de penetración del servicio de internet, su calidad y los ingresos percibidos:

El aumento o disminución de la variación porcentual trimestral del servicio de internet, cada 100 hogares por provincia,ingresos totales por año y tecnología, accesos por provincia y el promedio de Mbps por año.

# Diccionario de Carpetas y Archivos En Repositorio



    "CSV": "En esta carpeta se guardan los archivos descomprimidos de los dataset que se utilizaron"
        
        "Accesos_B_ancha_y_B_angosta_por_provincia.csv" archivo con el Número de accesos al servicio de Internet fijo por banda ancha y banda angosta en cada provincia

        "historico_velocidad_media_internet" archivo con la Serie histórica de la velocidad media de descarga de Internet por provincia (trimestral)

        "Internet_Ingresos_trimestrales_servicios_internet" archivo con los  Ingresos trimestrales de los operadores por el servicio de Internet fijo

        "Internet_penetracion_internet_por_cada_100_hogares" archivo con el Número de accesos al servicio de Internet fijo por cada 100 hogares por provincia

        "Internet_total_accesos_por_B_Aancha_y_B_angosta" archivo con el Número total de accesos al servicio de Internet fijo por banda ancha y banda angosta

        "Rangos_Internet_Accesos-por-velocidad_y_provincia" archivo con el Número de accesos al servicio de Internet fijo por velocidad de bajada en cada provincia por rangos

        "Serie_trimestral_internet_accesos-por-tecnologia" archivo con el Número de accesos al servicio de Internet fijo por tipo de tecnología. Total nacional (trimestral)

        "Telefonia_movil_Acceso_por_cada_100_habitantes" archivo con la Penetración del servicio de telefonía móvil (métrica: población)

        "Telefonia_movil_Ingresos_trimestrales" archivo con Ingresos trimestrales de los operadores por el servicio de telefonía móvil

        "TV_ingresos_trimestrales_servicios" archivo con los Ingresos trimestrales de los operadores por el servicio de televisión por suscripción y satelital (miles de $)

        "TV_total_accesos_suscripcion_y_satelital" archivo con el Número total de acesos a televisión por suscripción y satelital

    "EDA_PI_DA": "Aarchivo en formato .ipynb que se utilizó para realizar el análisis exploratorio de los datos."


    "Dashboard_PI_DA_Telecomunicaciones.pbix": "Es un archivo que contiene el dasboard en Power BI que incluyen procesos de transformación y analisis de datos para la presentación"

    "README" archivo con los textos descriptivos de todo el proyecto.




- Conclusiones

El acceso a Internet fijo, ha aumentado progresivamente desde el año 2014 y se ha acrecentado especialmente en los últimos años. Podemos razonar a partir de los datos, que la pandemia fue un factor fundamental para esta aceleración en la digitalización universal. No solo fue necesario para comunicarnos con nuestros seres queridos y compartir momentos de ocio, sino también para realizar todas las actividades de estudio y trabajo.

Asimismo, si bien se ha magnificado la actividad a través de las redes y a tecnología, la brecha entre los que aún no tienen acceso se ha hecho mas grande, siendo urgente así como oportuno, la posibilidad de generar accesos a las localidades que aún no tienen esta posibilidad que son un montón y se expresan en el presente proyecto.

También podemos observar que en la ubicación geográfica estas oportunidades se dan de manera centralizada entre las provincias de Buenos Aires y Córdoba como las que mas accesos a Internet tienen cada 100 hogares, siendo Tierra del Fuego una excepción pero que por ahí el dato está transgiversado por la cantidad de población en relación a la ocupación del territorio. Es una oportunidad para la empresa, facilitar el acceso a internet en estas regiones, así como también mejorar la velocidad de bajada (es decir la calidad de internet) para que el servicio sea mejor en todo el país. Nuevamente las provincias con menor velocidad media de bajada son las mas alejadas geográficamente de Buenos Aires.

Se observa que el cable modem y la fibra óptica aumentan casi a la par, aunque en los últimos trimestres se ve una disminución en el uso de cable modem y reemplazo por fibra óptica que los hogares eligen cada vez mas como tecnología para su conectividad. Es importante para el negocio estar al tanto de esta nueva demanda para poder satisfacer a los usuarios.

La suma de ingresos en lo que refiere a Internet viene en aumento. Finalmente y habiendo realizado una comparación con algunos datos de otras tablas, pude concluir que puede ser una buena idea sumar a estos servicios paquetes o promociones que incluyan suscripciones de TV para seguir impulsando el crecimiento de ambos servicios.