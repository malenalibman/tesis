Marco Teórico
=============

Debido a que este trabajo analiza, en esencia, una evaluación, se considera
necesario delinear los conceptos básicos referidos al monitoreo y la evaluación
de sistemas complejos como son las IDE.

### Evaluación y Monitoreo

Según Castelein y Manso Callejo (2010) el concepto de monitoreo se puede definir
como la capacidad de estar al tanto del estado de un sistema y ser capaz de
observar cambios en el mismo a través del tiempo. Basándose en la observación de
monitoreo de los sistemas, con criterios definidos se pueden hacer evaluaciones
o análisis de estándares.

Su uso permite comprender y mejorar lo evaluado, resumiendo, describiendo y
valorando los resultados. Éstos pueden ser usados para la toma de decisiones
sobre políticas y para resolver problemas de implementación.

Desde el punto de vista teórico, según Grus, Castelein, Crompvoets, Overduin,
Van Loenen, Van Groenestijn, Rajabifard y Bregt (2011), el razonamiento detrás
del marco de análisis o evaluación multicriterio se origina desde los principios
del estudio de sistemas complejos, donde el uso de múltiples métodos de análisis
en simultáneo proporciona un resultado de evaluación más holístico y menos
sesgado de fenómenos complejos. El estudio de las IDE como sistemas complejos,
combinando distintos puntos de vista, permite atender múltiples propósitos en la
evaluación, generando así una imagen más real de la IDE y permitiendo dar
respuesta a distintas necesidades de los actores clave.

### Infraestructuras de Datos Espaciales

El objeto de investigación principal en la evaluación de IDERA son las
Infraestructuras de Datos Espaciales (IDE), por lo cual debemos establecer de
qué se tratan para entender cómo se construye su monitoreo y evaluación.

La primera definición de una IDE, se realizó en Estados Unidos en 1994, para la
creación de la IDE Nacional, describiéndola como los medios de tecnología,
políticas, estándares y recursos humanos necesarios para adquirir, procesar,
almacenar, distribuir y mejorar la utilización de datos geoespaciales. Este
enfoque es en particular el de los objetivos de la IDE, según consta en
President of The United States (1994).

Pero, así como no existe una sola definición acerca de lo que es un Sistema de
Información Geográfica, tampoco existe una sola forma de describir qué es una
Infraestructura de Datos Espaciales.

Abad Power, Bernabé Poveda y Rodríguez Pascual (2012: 42) las definen como: “una
infraestructura que permita compartir, intercambiar, combinar, analizar y
acceder a los datos geográficos de forma estándar e interoperable”.

Para permitir esa serie de acciones, una IDE está conformada por los siguientes 
elementos: datos geográficos, servicios Interoperables y acuerdos. Estos elementos 
son generados a partir de su estructura, compuesta por: datos y sus metadatos, 
actores, tecnología, acuerdos políticos, normas y servicios. 

Es importante remarcar que el trabajo de la IDE no se apoya únicamente en
publicar (más que en compartir) la información geográfica, sino en la
construcción de una comunidad de actores, que generen los mencionados acuerdos
políticos y adapten las normas internacionales de manera tal que sean aplicables
en el contexto local de implementación. Esto es, la construcción de una
**institucionalidad** IDE.

Para realizar estas acciones, las IDE pueden poner a disposición una serie de
elementos básicos que se traducen en herramientas informáticas y documentos.
Vale mencionar, herramientas básicas sobre la **información geoespacial**, como
el Catálogo de objetos Geográficos (que busca normalizar la nomenclatura y los
atributos de la información geográfica que se publica), el Geoportal Web (como
punto de acceso a todos los productos y servicios que ofrece una IDE), los
**geoservicios y publicación** de datos geográficos (para su descubrimiento,
acceso y uso) y la documentación sobre estos datos publicados a través de los
**metadatos**.

Estos son los denominados Geoservicios Web, a través de los cuales se implementa
la Visualización de Mapas (Web Map Service - WMS) que pone a disposición las
capas de información a través de un Visor de Mapas o desde software de
visualización de capas, la Descarga de Capas (Web Feature Service - WFS) para
poder analizar y trabajar los datos con cualquier Sistema de Información
Geográfica (SIG) de escritorio (como puede ser QGIS) y el Catálogo de Metadatos
(Catalog Service for the Web - CSW) dónde se genera la documentación de la
información geográfica publicada de manera que se pueda descubrir y acceder a
ella.

Todas estas acciones, se canalizan a través de tecnologías ajustadas a los 
estándares del Open Geospatial Consortium (OGC), consorcio de empresas, agencias 
gubernamentales, instituciones de investigación y universidades, a cargo de crear 
las normas y estándares de tecnologías para la democratización de la información 
geográfica. Esto permite que cualquiera de las acciones definidas se pueda ejecutar 
en cualquier formato, lugar e idioma, hecho que se refuerza a través de la 
implementación de dichos estándares en la IDE nacional como uno de sus principales 
acuerdos.

Incluso publicaciones centradas SIG reconocen que ya no es posible hablar de SIG
sin hablar de IDE. Así, Luaces, Olaya y Fonts (2014: 745), afirman que: “Las
Infraestructuras de Datos Espaciales (IDE) son en la actualidad el elemento
básico para el aprovechamiento de la información geográfica a nivel global.
Desde su aparición, han supuesto un cambio conceptual en el ámbito SIG, y su
importancia en el contexto actual es innegable”.

Así, podemos ver que las IDE no tienen un solo enfoque para definirlas, ni para
construirlas. Por eso se pueden caracterizar como sistemas complejos
adaptativos, dónde sus componentes básicos son similares en todo el globo, pero
la forma en que se definen, implementan y usan, son disímiles de acuerdo a la
región, capacidad organizacional y estado de evolución.

Los sistemas complejos adaptativos son sistemas abiertos en los cuales
diferentes elementos pueden interactuar de manera dinámica para el intercambio
de información, autoorganizarse y crear diferentes circuitos de
retroalimentación, entre los cuales las causas y efectos generan relaciones no
lineales y en el cual el sistema como todo tiene propiedades emergentes que no
pueden ser entendidas por referencia a las partes individuales. Grus, Crompvoets
y Bregt (2007).

### Estándares e Interoperabilidad

En línea con Olaya y Turton (2014), se puede entender como un estándar a
cualquier documento o práctica que tenga por objeto armonizar los aspectos
técnicos de un determinado producto o servicio.

En tal sentido, todo estándar requiere, para operar efectivamente como tal, que
un grupo o comunidad lo acepte para definir, a su interior, las características
de ese producto o de ese servicio.

Si solamente es ese uso, tácitamente aceptado por la comunidad o grupo, el que
valida el estándar, se puede considerar al mismo como un estándar de facto. En
cambio, los estándares de iure, son aquellos que han sido promovidos por algún
ente oficial de normalización o cuyo uso ha sido impuesto con carácter legal.

A su vez, se considera un estándar abierto a aquel cuya definición se encuentre
disponible para cualquier persona que busque conocerla y utilizarla para el
desarrollo de sus actividades.

Por su parte, siguiendo a Erba, Duarte y Stiefel (2012), en su recorrido por las
distintas definiciones de interoperabilidad, se puede afirmar que, a nivel
general, se trata de la capacidad que posee una organización o un sistema para
trabajar en forma conjunta con otras organizaciones o sistemas que existan
actualmente o que se vayan a crear.

En términos más específicos, OGC, entiende la interoperabilidad como el trabajo 
desarrollado en forma recíproca entre distintas aplicaciones informáticas que 
permite prescindir de penosas tareas de conversión, importaciones y exportaciones 
de datos y otras barreras de acceso a los recursos distribuidos impuestas por la 
diversidad de entornos de procesamiento[^1].

[^1]: [The Open Geospatial Consortium \| OGC](https://www.opengeospatial.org/)

El International Organization for Standardization - Technical Committee (ISO/TC)
211, familia de normas ISO que apunta a la estandarización en el campo de la
información geográfica digital, normando métodos, herramientas y servicios para
datos, comprende a la interoperabilidad como la capacidad de los sistemas y sus
componentes en relación al intercambio de información y en cuanto al
procesamiento cooperativo entre las diferentes aplicaciones[^2].

[^2]: [ISO - TC211](https://committee.iso.org/home/tc211)

Así, siguiendo a Mansilla (2016), la estandarización y la normalización, lograda
a través de acuerdos institucionales, constituyen las herramientas fundamentales
para propiciar un mayor nivel de interoperabilidad.

### Metaevaluación

Para que una evaluación tenga un nivel de calidad aceptable, pruebe su validez y
consiga credibilidad entre usuarios potenciales, es necesario evaluarla en sí
misma, eso se llama Meta Evaluación, identificando fortalezas y debilidades para
la mejora de sus procesos de implementación, tal como se plantea en Castelein y
Manso Callejo (2010).

En ese sentido, la participación de los propios actores de una IDE, en el
proceso de monitoreo y evaluación es esencial para el aprovechamiento de estas
herramientas y resulta de utilidad en el cumplimiento de los objetivos de las
IDE.

Así, el monitoreo y evaluación de las IDE de Argentina, en base a las
experiencias tanto de IDERA como internacionales, no puede ser definido desde
afuera, ni únicamente desde la investigación académica, sino que debe realizarse
con la participación de los diversos actores que integran la comunidad de IDERA.
