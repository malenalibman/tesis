La evaluación de IDE de IDERA
=============================

Primera versión
---------------

Del estudio del Procedimiento para la Evaluación de una IDE desarrollado por
IDERA, puede afirmarse que la metodología elaborada tiene por objeto realizar la
evaluación y caracterización de cada IDE, en términos del grado de cumplimiento
de los estándares que han sido definidos en los documentos y recomendaciones de
IDERA.

En la propuesta de procedimiento original se propone comenzar a evaluar
únicamente las IDE que se encuentren adheridas a IDERA, que posean servicio de
visualización de mapas WMS, servicio de catálogo de metadatos CSW, Geoportal, el
informe anual presentado y que sean de máxima jerarquía en su jurisdicción de
ministerios nacionales, provincias, municipios y universidades públicas. Los
señalados constituyen los elementos mínimos que tiene en cuenta IDERA para que
una IDE debe tener para considerarse como tal y en funcionamiento.

Ello obedece a la necesidad de reducir la cantidad de IDE a controlar en
comparación con los nodos evaluados en la experiencia previa de seguimiento.
También se busca que cada IDE de máxima jerarquía se responsabilice por la
aplicación de los estándares por parte de los nodos que la integran.

Dicha metodología considera cuatro temas que a su vez se dividen en categorías,
donde cada una es representada por indicadores, definidos por recomendaciones y
estándares publicados por IDERA y en función de los cuales se articula la
metodología de evaluación:

**Institucionalidad (10%):** aspectos referidos a lo organizacional. Acorde a lo
desarrollado en el marco teórico respecto a la definición de una IDE, resulta
central para cada IDE contar con los acuerdos que consideran los indicadores que
se detallan a continuación, en línea con lo definido por la IDE nacional.

Así, sus categorías, siguiendo los indicadores propuestos por IDERA para evaluar
la institucionalidad, son: Adhesión a IDERA, Informe anual, Norma constitutiva,
Descentralización de la producción y Publicación de la información.

El primero de estos indicadores da cuenta de si el organismo se encuentra
adherido a IDERA y de la fecha en la que se firmó la correspondiente carta de
adhesión. La fuente de dicho dato son los registros que mantiene la Coordinación
Ejecutiva de IDERA. Vale recordar, que ello es requisito para ser susceptible de
ser evaluada.

El siguiente indicador es el Informe anual que debe presentar cada IDE a fin de
caracterizarla y conocer sus avances y situación actual. Este informe permite
conocer a la IDE y tener en cuenta sus particularidades a la hora de hacer la
evaluación y también es un requisito para poder ser evaluada.

A continuación, se analiza si la IDE ya cuenta con algún tipo de normativa
constitutiva, esta información puede provenir del Informe anual, de los
registros de la Coordinación Ejecutiva de IDERA o de la página del Geoportal de
la IDE. Ello es importante, tanto por dotar de una mayor institucionalidad a los
acuerdos previamente referidos, como por definir las incumbencias de la IDE y
otros aspectos de su organización, a través de un marco legal. Si bien no
garantiza su perdurabilidad en el tiempo, la existencia de un marco legal le
otorga mayor grado de institucionalidad y formalidad, lo cual puede contribuir a
mayores facilidades para obtener y sostener los recursos necesarios para el
funcionamiento de una IDE.

Por último, se analiza si la estructura de la IDE cumple con las recomendaciones
sobre el trabajo descentralizado. En particular, se busca asegurar que la
coordinación de cada IDE no concentre la información de todas las áreas de la
jurisdicción, sino que cada una tenga el reconocimiento correspondiente por los
datos o la responsabilidad de publicarlos como nodo. Dado que ello implica
señalar con precisión quién es legalmente responsable de la información
publicada y de su veracidad y, además, permite evitar que la centralización de
la información lleve a su veloz desactualización por falta de una comunicación
fluida entre los distintos actores que la generan. Una de las características de
una IDE es justamente la facilidad de contar con herramientas que permiten la
actualización sencilla y permanente de la información publicada por parte de sus
productores.

**Publicación y Geoservicios (30%):** considera cómo está publicada la
información geográfica y si dicha publicación resulta utilizable para los
usuarios. Dado que, como se señaló en el marco teórico, una IDE tiene que poder
generar algunas acciones sobre la información producida. Y la publicación y los
geoservicios es la forma en que se permite el acceso, análisis y uso de dicha
información a sus diversos usuarios.

Las categorías correspondientes a este tema son: Geoportal, Servicios de
Visualización de Mapas WMS, Descarga de Datos Básicos y Fundamentales (DByF) por
Servicio de Descarga WFS, Servicio de Descarga de capas WFS, Servicio de
Catálogo de metadatos CSW y Datos Abiertos o Descarga Masiva.

En la categoría de Geoportal, se analiza si cumple con las recomendaciones de
contenido, considerando al geoportal en sí mismo, por un lado, y al visualizador
y sus elementos mínimos, por el otro. Si bien IDERA ha elaborado un documento de
recomendaciones sobre Geoportal, aún no lo ha puesto a disposición de la
comunidad. Dado que el Geoportal es la puerta de entrada a la IDE que permite
acceder a todos los datos y servicios que ofrece, se busca, justamente,
garantizar que los contenidos resulten accesibles para el usuario, desde el
nivel básico.

La categoría de Servicios de Visualización de Mapas WMS busca establecer, además
de la publicación en el geoportal del enlace de acceso, su correcto
funcionamiento y configuración a través del análisis de las respuestas a las
peticiones Capacidades del Servicio (GetCapabilities), Visualización del Mapa
(GetMap) y Consulta de atributos del objeto (GetFeatureInfo). Adicionalmente, se
analiza si el servicio está siempre disponible o si suele tener inconvenientes a
lo largo del tiempo, a través del monitoreo de las respuestas al menos dos veces
al día.

El testeo de estas operaciones básicas del servicio WMS busca asegurar que los
usuarios puedan acceder a este servicio de visualización de mapas en cualquier
día y horario. Ello es importante, porque la accesibilidad para los usuarios es
un objetivo básico para cualquier IDE.

En su contenido, respecto a las capacidades del servicio, debería tener:

-   Las proyecciones recomendadas habilitadas (SRS), de modo tal de contemplar
    los dos sistemas de referencia espacial más utilizados a nivel mundial
    (WGS84 y Web Mercator) y el marco de referencia POSGAR 2007 a fin de
    representar al territorio nacional en sus correctas proporciones.

-   La URL al metadato en el catálogo (MetadataURL), a fin de poder acceder a
    los metadatos de la capa desde el servicio WMS.

-   Los metadatos completos del servicio en sí (nombre del servicio y datos de
    contacto de la IDE) para visualizar los datos de referencia de la IDE al
    usar el geoservicio.

-   El estilo de las capas (SLD), acorde a lo pedido por IDERA (aunque los
    estilos de base para las capas del catálogo no han sido publicados todavía
    por IDERA) con el objetivo de normalizar el aspecto de las capas de
    información del catálogo para todas las IDE, para su armoniosa visualización
    de conjunto, sobre todo en el visualizador de IDERA.

Así como resulta básico que los usuarios puedan acceder al servicio WMS, también
es crucial garantizar que puedan cumplir con las recomendaciones de IDERA
mínimas que apuntan al correcto funcionamiento y la máxima interoperabilidad
entre servicios.

Al respecto de la Descarga WFS de DByF, se plantea la existencia de un link por
separado del resto de los geoservicios para las capas de información geográfica
que entren en dicha categoría del Catálogo de Objetos Geográficos de IDERA[^6].

[^6]: [Definición de Datos Básicos y
Fundamentales](https://www.idera.gob.ar/images/stories/downloads/catalogo/DescripcinDByF_V2.0_IDERA.pdf)

Ello es importante para que el usuario pueda acceder con mayor facilidad a estas
capas básicas que IDERA ha definido como las de mayor importancia.

En relación con el servicio de descarga WFS, debe tener su enlace publicado en
el Geoportal. Ello es un elemento muy relevante en términos de transparencia, en
tanto demuestra voluntad por potenciar la usabilidad de los datos y facilitar su
pleno acceso a los usuarios.

En cuanto al servicio de metadatos CSW, debe poder accederse al mismo, que debe
tener todas las capas que existan en el WMS cargadas en el catálogo. En este
caso, la importancia de estos elementos radica en que permiten conocer la
existencia de los datos en sí, a través del catálogo, facilitando dos de las
acciones básicas de que debe permitir una IDE, como son la búsqueda y el
descubrimiento de la información. Además, aportan información clave para su
correcto uso, tal como su grado de actualización, autor y otras cuestiones
significativas (no existe aún un documento de IDERA que detalle cómo se
configura exitosamente el servicio CSW como hay para WMS).

A la vez que debe existir un link a un CSW que filtre las capas de DByF por
separado, teniendo en cuenta que se recomienda la publicación, mediante descarga
WFS, de dichas capas.

En la última categoría se evalúa la existencia de acceso a la información
publicada en formato de datos abiertos, ya sea como un Portal de Datos Abiertos
(Junar[^7] o CKAN[^8] son algunos ejemplos) o como links de descarga masiva.

[^7]: [Junar Data Platform](https://www.junar.com/)

[^8]: [ckan – The open source data portal software](https://ckan.org/)

**Información Geoespacial (30%):** es la categoría en la cual la información
publicada es evaluada en sí misma, capa por capa. Las categorías que se analizan
son: DByF publicados, Datos Temáticos Publicados, Linaje completo de Metadatos,
Normalización de nombres de capas y Actualización de los datos. Ello es
importante, porque el tener en cuenta las recomendaciones para la publicación de
la información geográfica, tiene por objetivo garantizar que los datos estén
estandarizados y sean utilizables.

En cuanto a los DByF, se observa si es que se encuentran publicados y si los
datos están normalizados de acuerdo al catálogo de objetos geográficos de IDERA;
en cuanto a los nombres de las capas, su estructura de atributos y la cobertura
de la jurisdicción correspondiente a la IDE.

La importancia de ello, radica justamente, en que se trata de los datos de mayor
relevancia, según lo ha establecido IDERA, más allá de que todavía no se haya
publicado un documento que defina qué organismos son responsables de la
producción y la publicación de cada uno de ellos. Tampoco IDERA ha detallado en
el documento que los describe, los criterios a utilizar para establecer la
calidad de dichos DByF.

Para los datos temáticos, se analiza específicamente sí coinciden con un objeto
del catálogo publicado por IDERA[^9] y si respetan su estructura. Estas
condiciones son básicas para garantizar la interoperabilidad.

[^9]: [Descripción del Catálogo de Objetos Geográficos de IDERA
v2.0](https://www.idera.gob.ar/images/stories/downloads/catalogo/Descripcion_Catalogo_IDERA_V3.pdf)

Con respecto al linaje, si bien es información que contiene el metadato, es
importante conocer los procesos de obtención de la información y su origen. Vale
aclarar que, si bien ello no es obligatorio en el perfil de metadatos de IDERA,
se considera un elemento indispensable para que el usuario pueda evaluar la
calidad de la información publicada, sus alcances y limitaciones.

En la categoría de normalización de nombres de capas, se analiza que, de acuerdo
a las recomendaciones, no posean caracteres especiales denominados ANSI (comas,
puntos, espacios, acentos, entre otros), que los títulos de las capas sean
acordes al catálogo (según corresponda) y que no haya más de una capa por objeto
del catálogo. Ello es imprescindible para garantizar que la información sea
identificable como tal de acuerdo al catálogo.

La última categoría busca chequear que la fecha de actualización de la
información coincida con el período de actualización previsto por el productor
del dato y consignada en el metadato de cada objeto. Estos dos valores se
encuentran consignados en los metadatos. Este cruce es necesario para
diferenciar los datos que se encuentran actualizados de aquellos que presentan
un retraso en su actualización, situación que es importante a la hora de
utilizar la información.

**Metadatos (30%):** La documentación de los datos y de los servicios publicados
debe cumplir con los contenidos mínimos de acuerdo a los perfiles de metadatos
publicados por IDERA. Las categorías que se analizan son: Validación y
Contenido. Ello es crucial para que el dato esté correctamente documentado de
forma tal que el usuario pueda conocer si cumple con sus necesidades.

La validación se realiza usando como base el correspondiente perfil de metadatos
de IDERA y busca asegurar que dichos metadatos tengan completos, como mínimo,
sus elementos obligatorios.

En cuanto al contenido, se espera que los metadatos tengan la fecha de
actualización (para que sea factible evaluar la categoría del tema anterior),
que figure el responsable de la producción del dato y el generador del metadato,
que estén completos y no haya datos por defecto en los metadatos de servicios,
que el título del metadato coincida con el del geoservicio y el catálogo de
objetos, ya sea de IDERA o el propio de la IDE y que se encuentre el link al
recurso, ya sea de descarga directa o el geoservicio.

La aplicación de la metodología requiere tener la información básica sobre el
funcionamiento de la IDE, por lo que estipula un pedido de informes desde IDERA.
El siguiente paso en el procedimiento es la evaluación, indicador por indicador,
a fin de tener un primer resultado, que luego se utilizará para asignar un valor
de puntaje a cada ítem.

El informe consta de unas 23 preguntas sobre Institucionalidad, Publicación y
Geoservicios y Metadatos, que apuntan a caracterizar a la IDE y permitir un
análisis más personalizado, de la misma forma en que se aplica para eSDI-Net+ de
acuerdo a Rix et al (2011), donde se generaba una especie de tarjeta de
identificación de la IDE. El planteo inicial en el desarrollo de la evaluación
era que esta información se recopilara en una Base de Datos de IDE de Argentina,
para continuar con el monitoreo inicial, más allá de la regularidad de las
evaluaciones, permitiendo así a la Coordinación Ejecutiva de IDERA acompañar a
las IDE en su desarrollo y evolución. Esto se asimila al proyecto eSDI-Net+, que
generó una base de datos[^10] que es pública, a fin de mejorar la operación de
las IDE subnacionales de Europa.

[^10]: [eSDI-Net+ Database of
SDI](https://esdinetplus.eu/best_practice/database.html)

En esta primera versión, con las herramientas disponibles, el proceso no se
encuentra automatizado en ninguna de sus tareas de relevamiento de datos, usando
como apoyo la información contenida en el informe descrito en el párrafo
precedente, así como los relevamientos previos de IDERA.

Para llegar al puntaje final correspondiente a cada IDE, se considera la
situación de cada uno de los indicadores descritos, tomando como referencia los
documentos elaborados por los Grupos de Trabajo (disponibles en el sitio web de
IDERA). Así, se asigna a la IDE, para cada indicador un puntaje acorde a su
cumplimiento, luego se pondera cada variable para arribar al valor
correspondiente a cada categoría y, finalmente, se pondera cada categoría, para
obtener el valor global de cada IDE. Tales ponderaciones obedecen a cuán
importante considera cada elemento (indicador y categoría), actualmente, la
comunidad de IDERA.

Una vez que se obtiene el valor total de cada IDE evaluada, se elabora el
correspondiente reporte, explicando dicho resultado, que debería ser revisado
por actores clave elegidos en el ámbito del Equipo Coordinador de IDERA.

Son estos actores quienes deben hacer una devolución, de modo tal que ese
reporte, validado y enriquecido por sus revisores, se remita a la IDE evaluada,
a los fines de que pueda conocer sus resultados y desarrollar las acciones que
considere pertinentes para mejorar su funcionamiento.

##### Cuadro 1 - Indicadores del tema Institucionalidad

|**Categoría**                                                |**Indicadores**                                   |**Documento publicado**                                   | **Método de evaluación**                                     |**Calificación**                                             |**Peso categoría** |**Peso tema** |
| ------------------------------------------------------------ | ------------------------------------------------- | :----------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------- | ------------- |
| Adhesión  a IDERA                                            | Fecha  de adhesión                                | [Adhesión a IDERA](http://www.idera.gob.ar/index.php?option=com_content&view=article&id=200&Itemid=267) | según  registros de IDERA                                    |                                                              |                      | 10%           |
| Informe  Anual                                               | Presentado  de acuerdo a estándar de IDERA        | Contenidos  mínimos para la presentación del informe anual de las IDE de máxima jerarquía | Si  cumple con el contenido mínimo puede evaluarse.          |                                                              |                      |               |
| Norma                                                        | Decreto  publicado en IDERA                       | [Recomendaciones   para la creación de un nodo IDE](http://www.idera.gob.ar/images/stories/downloads/documentos/Recomendaciones_para_la_creación_de_un_nodo_IDE.pdf) | Según  registros de IDERA y/o Geoportal, punto 9             | Norma  publicada: Sí/No                                      | 40%                  |               |
| Descentralización  de la producción y publicación de la información | Publicación  desde los productores de información | [Descripción   De Datos Básicos y Fundamentales](http://www.idera.gob.ar/images/stories/downloads/catalogo/DescripcinDByF_V2.0_IDERA.pdf)  <br />[Recomendaciones   para la creación de un nodo IDE de máxima jerarquía](https://www.idera.gob.ar/images/stories/downloads/documentos/guias/tecnologia/Recomendaciones_para_creacion_de_nodo_IDE.pdf) | Cada  capa debe tener identificado su autor y la URL del geoservicio original, del  productor responsable o designado para la producción y la publicación de la  información. En el caso que el catálogo de metadatos sea descentralizado, los  metadatos estarán cosechados del original. En base a puntos 12 y 16 del  documento de Recomendaciones para la conformación de un nodo IDE de máxima  jerarquía. De acuerdo a las recomendaciones establecidas, en caso de  centralizar la información de otros organismos (nodos), se deberá especificar  el origen de la información en el metadato, tanto en el linaje como en el  contacto del productor de la información | -Si  la información está en el metadato: 100%    - Si la información está en el "abstract" del servicio: 50%    - Si no está publicada: 0%    Adicionalmente debe estar especificado en el geoportal que nodos existen y  cuáles son sus recursos disponibles | 60%                  |               |

 


##### Cuadro 2 - Indicadores del tema Publicación y Geoservicios

| **Categoría**                     | **Indicadores**                                              | **Documento    publicado**                                   | **Método de evaluación**                                     | **Calificación** | **Peso   categoría** | **Peso tema** |
| --------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------- | :------------------: | :-----------: |
| Geoportal                         | Recomendaciones  para el contenido del geoportal             | Contenido  recomendado para el geoportal de una IDE de máxima jerarquía | Si se cumplen  todos los puntos obligatorios                 | 75%              |         20%          |      30%      |
| Visualizador                      | Contenido  recomendado para el geoportal de una IDE de máxima jerarquía | Visualizador  que funcione, que las herramientas de consulta de objetos devuelvan  información y que las capas de nodos fuera de la IDE u otras IDE estén por  WMS y no cargadas en el mismo (esto se chequea en el Informe Anual, donde  debería indicarse cómo se está organizado a nivel software y publicación) | 25%                                                          |                  |                      |               |
| WMS                               | GetCapabilities   GetMap                                     | [Recomendaciones   para servicios Web de Mapas](http://www.idera.gob.ar/images/stories/downloads/ide/IDERA-RecomendacionesparaServiciosWebdeMapasWMS_v1.2.pdf) | Debe devolver  un XML bien formado. Debe tener completados los datos que conforman los metadatos  automáticos del servicio: título, resumen, contacto | 15%              |         15%          |               |
| GetFeatureInfo                    | [Recomendaciones   para servicios Web de Mapas](http://www.idera.gob.ar/images/stories/downloads/ide/IDERA-RecomendacionesparaServiciosWebdeMapasWMS_v1.2.pdf) | Debe devolver  un XML bien formado                           | 10%                                                          |                  |                      |               |
| SRS                               | [Recomendaciones   para servicios Web de Mapas](http://www.idera.gob.ar/images/stories/downloads/ide/IDERA-RecomendacionesparaServiciosWebdeMapasWMS_v1.2.pdf) | Del GetCapabilities se obtiene la lista de SRS  habilitados y se puede comparar con la lista de los recomendados | 5%                                                           |                  |                      |               |
| SLD                               | [Recomendaciones   para servicios Web de Mapas](http://www.idera.gob.ar/images/stories/downloads/ide/IDERA-RecomendacionesparaServiciosWebdeMapasWMS_v1.2.pdf) | Verificar  visualmente si coincide con lo pedido             | 2%                                                           |                  |                      |               |
| Metadata URL                      | [Recomendaciones   para servicios Web de Mapas](http://www.idera.gob.ar/images/stories/downloads/ide/IDERA-RecomendacionesparaServiciosWebdeMapasWMS_v1.2.pdf) | Dentro del  GetCapabilities si aparece con el tag <metadata> en cada detalle de  cada capa | 30%                                                          |                  |                      |               |
| Metadatos del  Servicio en WMS    | [Recomendaciones   para servicios Web de Mapas](http://www.idera.gob.ar/images/stories/downloads/ide/IDERA-RecomendacionesparaServiciosWebdeMapasWMS_v1.2.pdf) | Observando el  GetCapabilities debe tener cargados los datos de contacto, título y resumen | 8%                                                           |                  |                      |               |
| Salud del  servicio               | No hay un  documento que estipule un mínimo                  | Se debe  realizar con un monitor de Geoservicios, con chequeos al menos dos veces por  día | 30%                                                          |                  |                      |               |
| WFS DByF                          | URL por  separado                                            | [Normalización de Capas para Servicios OGC](https://www.idera.gob.ar/images/stories/downloads/estandares/Normalizacin_de_capas_para_servicios_OGC.pdf)  <br />[Lineamientos   para el acceso, difusión, uso e interoperabilidad de información geoespacial](http://www.idera.gob.ar/images/stories/downloads/documentos/normativa/Lineamientos_acceso_difusion_uso_e_interoperabilidad_IG_v1-0.pdf) | Debe existir  la URL publicada en el geoportal, la salud se puede evaluar en el monitor de  geoservicios | Sí/No            |         30%          |      30%      |
| WFS                               | URL                                                          | [Configuración   WFS en Geoserver](http://www.idera.gob.ar/images/stories/downloads/documentos/guias/tecnologia/Instructivo_-Configuracion_WFS_en_GEOSERVER.pdf) | Debe existir  la URL publicada en el geoportal, la salud se puede evaluar en el monitor de  geoservicios | Sí/No            |          5%          |               |
| CSW                               | Todas las  capas                                             | No hay  documento de recomendaciones                         | Debe tener por cada capa publicada un registro de  metadatos | 75%              |         20%          |               |
| CSW DByF                          | generar en  Geonetwork el CSW filtrado                       | Mismas capas  que en el WFS de DByF                          | 25%                                                          |                  |                      |               |
| Datos Abiertos  o Descarga Masiva | Todas las  capas                                             | [Lineamientos   para el acceso, difusión, uso e interoperabilidad de información geoespacial](http://www.idera.gob.ar/images/stories/downloads/documentos/normativa/Lineamientos_acceso_difusion_uso_e_interoperabilidad_IG_v1-0.pdf) | Se  puede sugerir que en ausencia de un sistema de datos abiertos como junar o  ckan, se usen los links de descarga WFS | Sí/No            |         10%          |               |

 
 

##### Cuadro 3 - Indicadores del tema Información Geoespacial

| **Categoría**                      | **Indicadores**                                              | **Documento    publicado**                                   | **Método de evaluación**                                     | **Calificación**                                             | **Peso   categoría** | **Peso tema** |
| ---------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------- | ------------- |
| DByF  publicados                   | Publicados                                                   | [Descripción   de Datos Básicos y Fundamentales ](http://www.idera.gob.ar/images/stories/downloads/catalogo/DescripcinDByF_V2.0_IDERA.pdf) | Si el DByF  coincide con la estructura planteada en el documento (nombre, atributos) | 65%                                                          | 50%                  | 30%           |
| Acorde a  Catálogo de Datos        | [Descripción   del Catálogo de Objetos Geográficos](http://www.idera.gob.ar/images/stories/downloads/catalogo/DescripcinCatlogodeOG_V2.5_IDERA.pdf) | Manual, evalúa  nombre de las capas, existencia y coherencia de los atributos con el Catálogo  y completitud (en cuanto a cobertura completa) | 35%                                                          |                                                              |                      |               |
| Datos  Temáticos Publicados        | Catálogo de  Objetos Geográficos de IDERA                    | [Descripción   del Catálogo de Objetos Geográficos](http://www.idera.gob.ar/images/stories/downloads/catalogo/DescripcinCatlogodeOG_V2.5_IDERA.pdf) | Si el dato temático coincide con un objeto del  catálogo, debe estar acorde a la estructura del mismo (nombre, atributos) | Sí/No                                                        | 5%                   |               |
| Linaje  completo en Metadatos      | Perfil de  metadatos                                         | [Buenas   Prácticas en Metadatos](https://www.idera.gob.ar/images/stories/downloads/documentos/metadatos/20180202-Guia_de_Buenas_Practicas_de_Metadatos_V1_0.pdf) | Mínimamente  que posea los elementos obligatorios            | Sí/No                                                        | 10%                  |               |
| Normalización  de Nombres de capas |Nombre sin caracteres especiales<br />Título de acuerdo a catálogo<br />1 capa = 1  objeto del catálogo | [Normalización   de Capas para Servicios OGC](https://www.idera.gob.ar/images/stories/downloads/estandares/Normalizacin_de_capas_para_servicios_OGC.pdf) | Debe cumplir  con las condiciones de la recomendación del documento | Porcentaje de capas publicadas que  cumplen cada recomendación | 30%                  |               |
| Actualización                      | Fecha de  actualización del Recurso                          | [Perfil   de Metadatos para Datos Vectoriales](http://idera.gob.ar/images/stories/downloads/estandares/PMIDERA_Perfil_Metadatos_p_Datos_Vectoriales_IDERA_V2_0.pdf) | Verificación  en el metadato de la última fecha de actualización del recurso y del período  de actualización | 100% si es  menos de un año                                  | 5%                   |               |



##### Cuadro 4 - Indicadores del tema Metadatos

| **Categoría**                                           | **Indicadores**                                              | **Documento    publicado**                                   | **Método de evaluación**                                     | **Calificación** | **Peso   categoría** | **Peso tema** |
| ------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------- | -------------------- | ------------- |
| Validación                                              | ISO 19139                                                    | [IDERA - GitHub](https://github.com/idera/perfiles)          | Validador de  Geonetwork con la plantilla de IDERA           |                  |                      | 30%           |
| Contenido                                               | Fecha de  Actualización                                      | [Perfil   de Metadatos para Datos Vectoriales](http://idera.gob.ar/images/stories/downloads/estandares/PMIDERA_Perfil_Metadatos_p_Datos_Vectoriales_IDERA_V2_0.pdf) | Generados por  el catálogo al momento de insertar el metadato o su modificación | Sí/No            | 5%                   |               |
| Responsable                                             | [Perfil   de Metadatos para Datos Vectoriales](http://idera.gob.ar/images/stories/downloads/estandares/PMIDERA_Perfil_Metadatos_p_Datos_Vectoriales_IDERA_V2_0.pdf) | Verificar el  responsable del dato y el generador de metadato | Cantidad de  capas                                           | 30%              |                      |               |
| Metadatos del  Servicio en Catálogo de metadatos        | (en revisión  por Grupo Metadatos)                           | Metadato  creado y con elementos obligatorios completos, no por defecto | Cantidad de  capas                                           | 15%              |                      |               |
| Título  coincidente con geoservicio y Catálogo de datos | (en revisión  por Grupo Metadatos)                           | Verificación  con el WFS DByF y el catálogo, a partir del CSW de DByF | Cantidad de  capas                                           | 20%              |                      |               |
| Link al  Recurso                                        | [Buenas   Prácticas en Metadatos](https://www.idera.gob.ar/images/stories/downloads/documentos/metadatos/20180202-Guia_de_Buenas_Practicas_de_Metadatos_V1_0.pdf) | Comprobar que  el link del recurso del Metadato si posee un geoservicio (WMS / WFS) en el  Servidor de Mapa URL Metadata haga referencia al metadato donde se está  analizando este link | Sí/No                                                        | 30%              |                      |               |

##### *Fuente: elaboración propia en base al relevamiento realizado por el Instituto Geográfico Nacional*

En un primer momento, a fin de analizar la pertinencia y utilidad de la
evaluación desarrollada, como experiencia piloto se seleccionó la
Infraestructura de Datos Espaciales de Tucumán (IDET), entre otros factores, por
contar con cierta cultura de la evaluación, visible, por ejemplo, en el esfuerzo
por desarrollar una evaluación propia para sus distintos nodos (incluyendo
organizaciones de la sociedad civil y empresas), documentado en IDET (2017).

Como resultado de esa evaluación, según consta en el Acta de Reunión del Equipo
Coordinador de IDERA del 9 de marzo de 2018, la IDET se encontraba en un
excelente estado de cumplimiento de los estándares de IDERA, presentando un
valor global de 75%.

Descomponiendo ese número general, se advierten mejores resultados en los temas
de Información Geoespacial (83%) y Metadatos (87%) que en los de
Institucionalidad (60%) y Publicación y Geoservicios (60%).

A su vez, como ejemplo del tipo de recomendaciones que permite la evaluación,
para la mejora de las IDE, en el caso de la IDET, se señaló en cuanto a la
Institucionalidad, la necesidad de continuar con el proceso de generación de una
norma que le dé un marco legal a todo el trabajo que se está realizando; en
cuanto a Publicación y Geoservicios, se planteó que el servicio WMS solamente
tendría que agregar las proyecciones recomendadas a su configuración, ya que son
necesarias para asegurar la interoperabilidad, además de poner en las capas las
URL de los metadatos y normalizar los estilos.

Vale destacar que, en el proceso de esta prueba piloto, se presentaron sus
resultados a los revisores del Equipo Coordinador, sin que se hayan registrado,
por parte de los mismos, aportes relevantes.

Por otro lado, durante el dictado de (hasta ahora) dos ediciones del Seminario
de IDE de la Licenciatura en Sistemas de Información Geográfica de la
Universidad Nacional de Tres de Febrero, se ampliaron las observaciones piloto
sobre la evaluación de IDE de IDERA, en especial sobre qué aspectos funcionaban
mejor y en relación a cuáles presentaban mayores dificultades a la hora de
aplicarla. Vale consignar que la autora del presente trabajo formó parte de
estas experiencias (en 2018 como estudiante y en 2019 como auxiliar docente).

En ambas oportunidades, los estudiantes tuvieron la posibilidad de elegir las
IDE sobre las que intentarían aplicar la metodología de evaluación detallada
precedentemente. De muchas de estas experiencias (que incluyen también el
Seminario de IDE de la Facultad de Filosofía y Letras de la Universidad de
Buenos Aires dictado en 2019) han surgido interrogantes sobre el proceso y la
metodología de evaluación que se han considerado en los análisis desarrollados
en el presente trabajo.


