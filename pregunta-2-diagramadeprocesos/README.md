# INTEGRACION DE SISTEMA POS PARA EL E-COMMERCE MACY’S
 
 








Índice

1.	Introducción	4
1.1.	Objetivo	4
1.2.	Alcance	4
2.	Marco Teórico	4
3.	Descripción del problema o situación actual	5
4.	Diagrama del Flujo funcional del proceso, área o entidad	9
5.	Metodología de la solución	10
6.	Diccionario de datos	12
7.	Modelo o esquema de integración	13
8.	Arquitectura	14
9.	Solución desarrollada	15
10.	Conclusiones y/o Recomendaciones	16
11.	Trabajos futuros	18
12.	Terminologías	21
13.	Bibliografía	22

















1.	Negocio
Macy's ofrece experiencias y surtidos distintivos, incluida la familia más buscada de marcas exclusivas y de moda para él, ella y su hogar. 
Macy's, Inc. es uno de los principales minoristas del país con ventas en el año fiscal 2018 de $ 24,971 mil millones y aproximadamente 125,000 empleados. La compañía opera grandes almacenes bajo las placas de identificación Macy's y Bloomingdale's, y tiendas especializadas que incluyen Bloomingdale's The Outlet, Bluemercury y Macy's Backstage. Macy's, Inc. opera tiendas en 43 estados, el Distrito de Columbia, Guam y Puerto Rico, así como macys.com, bloomingdales.com y bluemercury.com. Las tiendas de Bloomingdale en Dubai y Kuwait son operadas por Al Tayer Group LLC bajo acuerdos de licencia. Macy's, Inc. con sede en la ciudad de Nueva York.
Los compradores pueden esperar grandes ahorros en ropa para hombres, mujeres y niños, así como ofertas en una variedad de artículos para el hogar, textiles y decoración para el hogar, cosméticos, cuidado del cabello y las uñas, regalos, joyas, zapatos, bolsos de diseño, accesorios y ropa deportiva.

2.	Problema del Negocio
Los problemas de más evidencia en la empresa son:
•	Posee un deficiente manejo de su inventario
•	No posee la opción de cotización para los clientes
•	Deficiente sistema de oferta
•	Confusión en los trabajadores por falta de Roles

3.	Objetivo
Optimización del proceso de gestión de inventario mediante la
Integración con el módulo de ventas a clientes, para reducir el tiempo de actualización de stock.

4.	Marco Teórico
Del latín” integratĭo,-ōnis” , la integración es el proceso por el cual las cosas se usen y se adhieren a otras para constituir un todo, completar un todo con las partes que faltaban, hacer que alguien o algo pase a formar parte de un todo. Fusionar dos o mas conceptos, corrientes, entidades, etc., divergentes entre si, en una sola que las sintetice. (Real Academia Española, 2019)
Permitir que sistemas puedan interoperar, esto es, intercambiar informaciones y servicios de forma transparente, sin tomar en cuentas las diferencias tecnológicas ni las diferencias de representación de información. (AEC, 2012)
Proceso de interconectar sistemas heterogéneos para crear un sistema mayor, con el objetivo de proveer servicios integrales. (ISOTools Excellence, 2014).
El concepto de integración de sistemas se planteó desde el nacimiento de la seguridad electrónica. Se hace posible hoy gracias a la presencia de grandes corporaciones, capaces de implementar los medios para manejar, desde un mismo control, los diferentes rubros que integran la seguridad. Distintos especialistas analizan y explican de qué se trata la integración y cuáles son las posibilidades de implementarla. (Guzmán, 2016)
La Integración de datos el proceso que permite combinar datos heterogéneos de muchas fuentes diferentes en la forma y estructura de una única aplicación. Esto facilita que diferentes tipos de información, tales como matrices de datos, documentos y tablas, sean fusionados por usuarios, organizaciones y aplicaciones para un uso personal, de procesos de negocio o de funciones.
La integración soporta el procesamiento analítico de grandes conjuntos de datos alineando, combinando y presentando cada conjunto de informaciones de departamentos organizacionales y fuentes de datos remotas y externas, para cumplir con los objetivos del integrador.
La integración de datos se implementa generalmente en un data warehouse mediante software especializado que aloja grandes almacenes de datos de recursos internos y externos. Los datos se extraen, se mezclan y se presentan de forma unificada. Por ejemplo, el conjunto completo de datos de un usuario puede incluir información extraída y combinada de marketing, ventas y operaciones, que se combinan para formar un informe completo. (PowerData, 2017).

5.	Descripción del problema o situación actual
En nuestro país vemos reflejado el crecimiento económico en mayor medida por la gran cantidad de empresas u organizaciones dedicadas a la venta de productos que en su mayoría son realizadas bajo la modalidad tradicional, es decir, persona a persona. Bajo esta modalidad las empresas estuvieron teniendo un crecimiento sostenible a lo largo del tiempo teniendo en cuenta el concepto de las ventas presenciales, pero debido al auge de tecnologías y la comercialización digital, las empresas tuvieron que buscar la manera de poder adaptarse a estas tecnologías con el fin de poder subsistir y generar más ganancias en un mercado emergente y altamente competitivo.

La necesidad de enfocar las ventas bajo este nuevo concepto y tendencias fue un reto para todas las empresas, porque tuvieron que remodelar su modelo de negocio como la idea y planteamiento de procesos a los cuales estaban acostumbrados, dicho modelo fue cambiando para adaptarse a estos cambios teniendo en cuenta un concepto que fue adquiriendo fuerzas a través del tiempo: el E-commerce.

El e-commerce tiene como concepto principal orientar el modelo de ventas al ámbito tecnológico, usando recursos tales como los recursos web, pagos electrónicos y distintos medios tecnológicos para aprovechar la alta dispersión del uso de aparatos tecnológicos y móviles, además del uso globalizado del internet como medio para el desarrollo y dispersión del internet.

El comercio electrónico, también conocido como e-commerce1 (electronic commerce en inglés) o bien comercio por Internet o comercio en línea, consiste en la compra y venta de productos o de servicios a través de medios electrónicos, tales como redes sociales y otras páginas web.

Originalmente, el término se aplicaba a la realización de transacciones mediante medios electrónicos tales como el Intercambio electrónico de datos; sin embargo, con el advenimiento del Internet y del World Wide Web, a mediados de la década de 1990 comenzó a referirse principalmente a la venta de bienes y servicios a través de Internet, usando como forma de pago medios electrónicos tales como las tarjetas de crédito.

La cantidad de comercio llevada a cabo electrónicamente ha crecido de manera extraordinaria debido a Internet. Una gran variedad de comercio se realiza de esta manera, estimulando la creación y utilización de innovaciones como la transferencia de fondos electrónica, la administración de cadenas de suministro, el marketing en Internet, el procesamiento de transacciones en línea (OLTP), el intercambio electrónico de datos (EDI), los sistemas de administración del inventario y los sistemas automatizados de recolección de datos.

La mayor parte del comercio electrónico consiste en la compra y venta de productos o servicios entre personas y empresas, sin embargo, un porcentaje considerable del comercio electrónico consiste en la adquisición de artículos virtuales (software y derivados en su mayoría), tales como el acceso a contenido "Premium" de un sitio web. En este sentido, hay multitud de plataformas en la nube donde te puedes crear tu propio comercio electrónico.

En los contratos de comercio electrónico el proveedor tiene un fuerte deber de información, que incluye todos los datos necesarios para usar correctamente el medio electrónico que se usa para la compra, los datos necesarios para comprender los riesgos de la contratación por ese medio electrónico y quién asume dichos riesgos y la información sobre el derecho a dejar sin efecto el contrato de compra.
		
El proyecto está orientado a una empresa dedicada al rubro de ventas, que cuenta con dos áreas, gerencias o módulos principales, los cuales en su mayoría contienen 3 módulos principales para un funcionamiento correcto: Modulo de ventas, compra e inventario o almacén, los cuales funcionan de manera macro para poder el flujo de ventas de manera muchísimo más rápida de la manera tradicional, lo cual en su mayoría de empresas suele ser muchísimo más complicada que realizarlas de manera física, puesto que las necesidades tecnológicas van a ir enfocadas a desarrollar una solución muchísimo más rápida y los casos de uso con sus respectivos escenarios para ser solucionados.

Es por ese motivo que surge la necesidad de implementar la tecnología a un proceso de gran demanda, para facilitar el proceso natural como el rendimiento de la misma, aprovechando al máximo las distintas formas y maneras de poder tomar ventaja de las tecnologías crecientes.

El e-commerce en Perú es un modelo de negocio que está evolucionando. Según data de Ipsos, más de 3 millones de usuarios en el país compran en línea y esta cifra junto con la de las compras online va en aumento. Actualmente, contamos con la presencia de la CAPECE (Cámara Peruana de Comercio Electrónico), una plataforma de transformación digital que reúne a los máximos exponentes del comercio electrónico del Perú que ayuda a empresas y emprendedores a dar el salto al canal online.
El e-commerce representa un canal adicional donde podemos ofrecer nuestros productos o servicios, lo que significa que podríamos aumentar el segmento de nuestro mercado a niveles exponenciales e incluso expandir fronteras y explorar el mercado internacional, brindando mayor cobertura. A veces los costos de tener una tienda física son muy elevados, pero con este modelo de negocio, los emprendimientos que están en sus inicios, incluso los que ya llevan tiempo operando, pueden ahorrar en costos fijos y al mismo tiempo ofrecer una experiencia completa y satisfactoria a sus clientes.
El comercio electrónico ha experimentado una notable evolución, pasando de ser un simple catálogo de productos o servicios, construido a partir de una página estática, a convertirse en un medio eficaz para realizar negocios. Existen tres tipos de comercio electrónico: Business to Business (B2B), Business to Consumer (B2C) y Consumer to Consumer (C2C). Estados Unidos y los países europeos y asiáticos han sido los pioneros en adoptar esta tendencia comercial. No obstante, hoy Estados Unidos y Europa parecen estancados en su evolución.

 Según el “Global B2C E-commerce” Europa ($482.3bn) y Norteamérica ($452.4bn) se encuentran entre las primeras regiones donde más facturación se genera. Sin embargo, en la actualidad, quien tiene un mayor crecimiento es Asia-Pacifico (un 44.5%) con una facturación en el 2013 de 567.3bn de dólares. De igual forma Latinoamérica muestra una gran evolución, con un crecimiento del 21.5% y una facturación de $33.2bn. Los países de esta región que hoy más compran por Internet son: Brasil, Venezuela, Argentina, Colombia, México, Perú y Chile. ComScore afirma que ocho de cada diez consumidores latinoamericanos buscan, investigan y compran productos en línea semanalmente.

Actualmente el comercio electrónico ha experimentado un fuerte crecimiento a nivel global, tanto en volumen de usuarios como de sitios comerciales; sin duda alguna la inversión en publicidad ha contribuido a su acelerado desarrollo de una manera exponencial. Hoy es la manera fácil y rápida de hacer negocios sin necesidad de grandes inversiones, desde la comodidad de su hogar u oficina, pues solo se requiere un computador y acceso a Internet.

La cultura del comercio electrónico cada día está tomando mayor fuerza en todo el mundo debido a las diferentes bondades que ofrece el eCommerce: comodidad, agilidad, seguridad, facilidad de pago, evita desplazamiento, restricción de horarios, filas, aglomeraciones que suelen ser incómodas y estresantes. En conjunto significa una optimización del tiempo.

Todo esto ha ido evolucionando gracias a las posibilidades que ofrece Internet, como es tener el mercado internacional a un clic, donde se encuentran todo tipo de productos y servicios que buscan satisfacer las necesidades de los compradores. De igual forma los gigantes del comercio electrónico como eBay, Amazon, Walmart, Aliexpress, Alibaba o Mercadolibre ofrecen plataformas seguras que cada día mejoran las condiciones de servicio postventa, garantía del producto, entrega oportuna, con las especificaciones requeridas, promociones, descuentos y demás estrategias que invitan al comprador a regresar.

Una clara tendencia del mercado electrónico es el auge de los teléfonos inteligentes y cómo a través de estos no solo se puede estar conectado en todo momento y lugar, sino que también es posible adquirir productos y servicios a un solo clic a través de las aplicaciones, situación que ha despertado no solo el interés de los clientes, sino de las empresas por estar ahí ofertando y vendiendo.

Estrategias de mercado como el Black Friday, realizada el 23 de noviembre en Estados Unidos, están siendo adoptadas cada día por países Latinoamericanos, de igual forma el Cyberlunes, táctica del mercado colombiano que tiene descuentos sin precedentes que sobrepasan el 50% en todas las marcas. Según la Cámara Colombiana de Comercio Electrónico, la jornada que tuvo lugar en mayo de 2014, se lograron 150 mil transacciones y las ventas representaron más de 38 mil millones de pesos colombianos, lo que se traduce en un incremento del 41% respecto a la edición anterior.

 Un reporte de eMarketer señala que las ventas online B2C alcanzarán, alrededor del mundo, US$1,5 trillones durante el año 2014. Esto supone un incremento del 20% en comparación con 2013.

La industria del comercio electrónico en el mundo registra transacciones de miles de millones de dólares anuales. De acuerdo con el informe “Global B2C E-commerce”, en el 2014 el mercado del comercio electrónico facturará 1.907 billones de dólares, es decir, experimentará un crecimiento del 22.9%. Se espera que en el año 2015 el comercio electrónico crezca un 18%, llegando a los 2.251bn de dólares.

De acuerdo con el “Estudio de OBS sobre El Comercio Electrónico 2014”, se estima que, entre 2012 y 2017, el crecimiento anual en B2C de la zona Asia-Pacífico será de un 28.53% y en América Latina de un 14.96%. Por otro lado, aunque África y Medio Oriente poseen las cifras estimadas más bajas en facturación, cabe destacar que muestran un promedio de crecimiento anual del 20.26%. 

6.	Diagrama del Flujo funcional del proceso, área o entidad
 
 

7.	Metodología de la solución
Este proyecto será implementado en un ambiente ágil, donde prime la colaboración y cuyo objetivo es el desarrollo del sistema de forma constante y orientada a resultados.
Es así como se usará la Metodología Ágil SCRUM para el desarrollo de nuestro proyecto. 
 
 
8.	Diccionario de datos

 


9.	Modelo o esquema de integración
El modelo a seguir será enfocado a atacar el problema a solucionar, en este caso centralizar la información de dos bases de datos, seguir las reglas de negocio de los módulos a integrar, y las interfaces que muestren las acciones en relación a la información solicitada del repositorio de datos creado.
 
10.	Arquitectura 
 

11.	Prototipo de la interfaz de la solución

 
 

 











12.	Solución desarrollada
La solución se basa en establecer una conexión entre las bases de datos usadas con una tercera base de datos la cual se ha reestructurado para usarse con el sistema modular nuevo, esta base de datos centralizada y en distintos lugares se cumplen los principios de alta disponibilidad y rapidez.
A continuación se presentan diagramas entorno a la solución de software  y el diagrama de base de datos centralizada


  


  





13.	Conclusiones y/o Recomendaciones
Luego de realizar la integración de los sistemas como parte del proyecto, podemos llegar a las siguientes conclusiones, que en su mayoría fueron evidentes al momento de realizar la integración como tal, las cuales apoyan en distintos grados a los proyectos o sistemas ya implementados:

•	Automatización de procesos. 
La automatización de procesos que ofrece la integración ayuda a que con menos esfuerzo se logre una productividad mayor. El hecho de que un sistema integrado pueda trasladar datos de unos elementos a otros ayuda a eliminar acciones que consumen tiempo y recursos de la empresa y que en los sistemas aislados no podemos evitar.

•	Optimización de la gestión de la información. 
La cantidad de información de la que dispone una organización para el desarrollo de su actividad es enorme, por eso es importante una gestión óptima de la misma. La integración de sistemas ayuda a esa gestión porque supone una mayor organización y mejor accesibilidad a aquellos elementos clave que empresarios y trabajadores deben conocer para la mejora del negocio. La búsqueda de datos, la obtención de informes económicos o de gestión es mucho más ágil y simple en un sistema integrado.

•	Simplificación en la actualización de sistemas. 
Las mejoras constantes que se incorporan a los sistemas de gestión requieren una continua actualización de los mismos para adaptarse a las nuevas normas, requerimientos del mercado, etc. La integración ayuda a estos procesos de actualización, ya que simplifica la incorporación de nuevos elementos sin tener que acceder de manera individual a cada uno de ellos.

•	Reducción de costes. 
Tanto el coste de adquisición como el mantenimiento de los sistemas de gestión se reduce cuando se dispone de una unidad integrada en relación a elementos individualizados. De igual manera la incorporación de nuevos sistemas suele ser más económico cuando se tratan de unidades de una herramienta ya existente frente la adquisición de una nueva aplicación individualizada.

•	Simplificación en la formación del personal.
A la hora de que los trabajadores aprendan a manejar y gestionar los sistemas el proceso es más sencillo cuando éstos están integrados, teniendo que familiarizarse sólo con el uso de una o unas pocas herramientas. Algo que no ocurre si éstas están individualizadas, cuyo uso es muy diferente en casa caso y se necesita conocer los diferentes sistemas y su manejo.

•	Agiliza los procedimientos de mejora continua. 
Las herramientas de gestión son una de las bases en las que las empresas han de establecer procesos de mejora continua. La planificación y ejecución de determinadas estrategias de producción o ventas han de acompañarse de un control de resultados que ayude a detectar errores o desviaciones sobre los objetivos marcados. Si los sistemas de gestión están integrados ese control es más sencillo y rápido, lo que permite una mejor toma de decisiones a la hora de reorientar esas estrategias.

•	Permite simplificar la incorporación de nuevos sistemas o funcionalidades. 
La rapidez a la que evoluciona el mercado o los continuos cambios de uso o costumbres de los clientes obligan a las empresas a incorporar a su negocio nuevos sistemas o funcionalidades en sus herramientas de gestión. Incorporarlos en forma de aplicaciones individuales supone un problema y un consumo de recursos mucho mayor que añadir esas nuevas funcionalidades a un sistema que ya conocemos y que se integra en el mecanismo de gestión que ya venimos utilizando.

Algunas recomendaciones que se deberían de tener en cuenta para la correcta integración de sistemas son las siguientes:

•	Comprender la integración del usuario con la organización a la que pertenece y su puesto de trabajo. Con esta recomendación, se sugiere a la organización que revise aspectos de integración del usuario a la empresa y a la tarea que realiza. 

•	Asegurar que el medio ambiente en el que se encuentra el usuario sea adecuado, además de validar que el sistema se desarrolle en un ecosistema necesario para el desarrollo progresivo del mismo. Con esta recomendación, se sugiere a la organización que examine algunos aspectos como, por ejemplo, las horas extras que se trabaja o las jornadas que incluyen días especiales, como casos similares. 

•	Asegurar una comunicación eficaz de cuestiones relacionadas al SI. Con esta recomendación, se sugiere a la organización que revise el estilo de comunicación, especialmente la comunicación respecto al cambio del SI, los diferentes medios de comunicación empleados para dar conocimiento al usuario del nuevo SI. 

•	Desarrollar estrategias de participación de los usuarios en la definición del SI para asegurar su compromiso y toma de conciencia con el cambio. Con esta recomendación, se sugiere a la organización que examine el estilo de participación empleado en la definición del SI.

•	Asegurar que se cumplan los requerimientos funcionales del SI. Con esta recomendación, se sugiere a la organización que examine los Requerimientos Funcionales. 
•	Asegurar el cumplimiento de los requerimientos no funcionales del SI como, por ejemplo, interfaces de usuario, performance, interfaces de software, etc. Con esta recomendación, se sugiere a la organización que revise los requerimientos no funcionales. 

•	Desarrollar estrategias de capacitación de los usuarios para el uso del SI, capitalizar su experiencia en el negocio y aspectos técnicos complementarios al uso del SI. Con esta recomendación, se sugiere a la organización examinar las necesidades de formación para el uso del SI y cuestiones relacionadas al conocimiento que requiere el usuario respecto a la tarea que realiza como así también conocimientos técnicos complementarios.

14.	Trabajos futuros
Existen diversas mejoras que se pueden llegar a implementar a fin de poder mejorar aún más la integración realizada a niveles tanto de programación, automatización, organización y demás para poder afianzar la integración ya realizada, con el fin de hacerla mucho más robusta y no tan endeble a sufrir con posibles escenarios no previstos por los casos de uso o definiciones adicionales que no sean parte de la integración.
Existen diversas mejoras o implementaciones posteriores que pueden servir de apoyo a la integración ya establecida con el objetivo de mejorarla o hacer que su funcionamiento sea mucho óptimo de lo normal.
Dichas mejoras o implementaciones posteriores pueden ser consideradas:

•	Mejor Planificación del trabajo: Es necesario determinar los objetivos a alcanzar, delimitar tiempos y fechas de entrega para poder realizar un monitoreo constante de avances y resultados.

•	Se debe de someter a una profunda evaluación la infraestructura de la empresa para determinar si se cuenta con las herramientas necesarias o si es necesario adquirir nuevos equipos, herramientas y/o personal.

•	Implementear Monitoreo y control del trabajo: Una situación típica dentro de las empresas son las denominadas “juntas de trabajo elefante”, las cuales son largas y pesadas. Por lo que resulta de suma importancia definir a los personajes responsables de cada actividad, así como de la persona encargada de realizar la tarea de monitoreo de avances en la actividad para mitigar los riesgos y poder optimizar los recursos, generando un mejor aprovechamiento de la planificación.

•	Gestión de acuerdos con proveedores: Es necesario realizar una evaluación periódica a los proveedores acerca de los acuerdos comerciales previamente establecidos con el afán de que los tiempos de entrega no se modifiquen durante el desarrollo del proyecto, viéndose comprometido el precio establecido en las negociaciones, ya que de lo contrario esto se refleja directamente en nuestras utilidades o en el bolsillo de los clientes.

•	Gestión de requerimientos: Esta etapa no se debe de realizar de forma obligada. Aunque eso sí, resulta de mucha utilidad, ya que puede ayudarnos a detectar ciertas vulnerabilidades de las cuales no estábamos conscientes.

•	Medición y análisis: ¿Cómo saber si estamos alcanzando los objetivos planteados? Parte fundamental de la planeación son los KPI’s de las distintas áreas involucradas. Dependiendo de la magnitud del proyecto, la periodicidad puede variar. Es importante medir los KPI´s con base en un sistema que nos brinde tres principales rangos de cumplimiento (100 a 80 verde, 79 a 50 amarillo, 49 a 0 rojo.)

•	Aseguramiento de la calidad de los procesos y el producto: Con base en los estándares de calidad previamente establecidos, se debe evaluar la calidad del producto. En el caso de los servicios se puede recurrir a encuestas de satisfacción profundamente perceptuales; estas pruebas deben de ser estandarizadas para no comprometer la calidad en futuras evaluaciones.

•	Gestión de configuración: El proceso de clasificación de repositorios es una tarea que al repetir toda la producción nos ahorra muchos dolores de cabeza. Hay que delimitar los formatos de nomenclatura y abreviaturas, destinos de almacenamiento y periodicidad de respaldos.

•	Entrega del servicio: Es necesario para poder finalizar la integración, asegurarnos de qué forma se entrega nuestro producto o servicio y cómo se percibe, ya que en muchas ocasiones las empresas se desentienden del proceso al realizar la entrega a los distribuidores o intermediarios.

Algunos beneficios de la implementación de la integración de procesos dentro de las organizaciones son:
•	La mejora de la visibilidad del proyecto
•	La comunicación interna interdepartamental
•	La calidad en los sistemas de servicio
Una de las soluciones a futuro que se deben de llegar a implementar es la integración completa de datos, esto a fin de poder trabajar de manera mucho más concreta con los distintos módulos con los cuales trabajará la empresa dedicada al e-commerce, los cuales beneficiarían a la integración de mejor manera, teniendo en cuenta los siguientes ejemplos:

	Reduce la carga sobre los analistas de negocios. Los profesionales del Business Intelligence se enfrentan a una carga de trabajo abrumadora tratando de filtrar las enormes cantidades de datos que entran a la empresa en el día a día. La eliminación de los silos de datos permite a los usuarios acceder a diferentes conjuntos de información basada en sus necesidades específicas. Dar a los equipos acceso directo a información relevante deja a los analistas con un tema menos del que preocuparse, permitiéndoles dedicarse a conjuntos de datos más complejos que generan valor para el negocio.
	Eliminar doble trabajo. En muchas ocasiones, algunas organizaciones realizan un análisis de clientes para conocer sus demandas, y poco después descubren que un proyecto similar se completó hace unos meses en otro departamento. Con una integración de datos se puede evitar esa redundancia y no sólo en términos de grandes proyectos. Los problemas más comunes a los que se enfrentan las empresas tienen que ver con registros de datos de clientes en múltiples lugares, documentación de procesos en distintos sistemas, etc.
	Maximiza el valor de los datos. Un análisis que puede ser eficaz para 20 de los empleados será considerablemente menos valioso si sólo cinco de ellos reciben el informe. Unificar datos a través de distintos canales permite a las organizaciones aprovechar distintos tipos de datos conjuntamente con otros para maximizar su potencial y garantizar que los grupos de usuarios tienen la visibilidad que necesitan. Esta transparencia puede extenderse a interesados tanto internos como externos impulsando la colaboración dentro de la empresa.
	Mejora la toma de decisiones. Dar a los usuarios acceso a datos clave incorporados en las aplicaciones y servicios que utilizan les permite tomar mejores decisiones al interactuar con clientes y colaboradores. La integración de datos en los sistemas relevantes hace que la información sea accionable en las operaciones diarias, proporcionando a los usuarios las ideas que necesitan para trabajar con la mayor inteligencia posible.
	Aprovechar los diversos tipos de datos. Si bien el aprovechamiento de tipos de datos variados está relacionado con la maximización del valor de los datos, es importante reconocer que los distintos tipos de información crean desafíos únicos. La información de las hojas de cálculo, las bases de datos altamente estructuradas, informes de social media, diagramas, documentos técnicos, y una amplia gama de otras fuentes, deben unirse para obtener información completa de las operaciones, especialmente cuando tecnologías emergentes como el internet de las cosas traen todavía más datos a los ecosistemas empresariales. Esta diversidad puede llegar fácilmente a ser abrumadora y hacer que los datos se dejen abandonados si los usuarios no tienen acceso a ellos para aprovechar la información intuitivamente a través de sus departamentos.












15.	Terminologías
•	Interoperabilidad de Sistemas:
Habilidad de dos o más componentes de software de cooperar, sin considerar sus diferencias en lenguajes de programación, interfaces y plataformas de ejecución.

•	Procedimiento:
Es un conjunto de acciones u operaciones que tienen que realizarse de la misma forma, para obtener siempre el mismo resultado bajo las mismas circunstancias

•	Aplicaciones:
Es simplemente un programa informático creado para llevar a cabo o facilitar una tarea en un dispositivo informático. Cabe destacar que, aunque todas las aplicaciones son programas, no todos los programas son aplicaciones. (Sistemas Master, 2018)

•	Infraestructura:
Hace referencia a un conglomerado de servicios, dispositivos físicos y aplicaciones de software que forman el sostén de los sistemas, funcionamiento de tareas y comunicaciones en cualquier compañía. (Grupo Garatu, 2020)

•	Datos:
Información concreta sobre hechos, elementos, etc., que permite estudiarlos, analizarlos o conocerlos. (Definicion, 2017)

•	Heterogeneidad de las Aplicaciones:
La causa de heterogeneidad puede estar en el tipo de aplicaciones, el modo de tratar los datos (de los sistemas de gestión de datos a las herramientas de recuperación de información textual), y en las plataformas o lenguajes de implementación en la que fueron desarrollados.


16.	Bibliografía
(2017). Obtenido de Definicion: https://definicion.de/datos/
(Febrero de 2020). Obtenido de Grupo Garatu: https://garatucloud.com/tecnologia-informatica-infraestructura-ti-redes-virtualizacion/
AEC. (Febrero de 2012). Obtenido de https://www.aec.es/web/guest/centro-conocimiento/integracion-de-sistemas
Deloitte. (Enero de 2020). Obtenido de https://www2.deloitte.com/es/es/pages/technology/solutions/integracion-de-sistemas.html
Real Academia Española. (2019). Obtenido de https://dle.rae.es/integrar
Sistemas Master. (Noviembre de 2018). Obtenido de https://sistemas.com/aplicacion.php

