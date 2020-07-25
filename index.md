## Cloud Computing: investigación de Alejandro Quesada y Jose Álvarez para CE-1103.
### Índice 
1. Definición e historia de Cloud Computing
2. Conceptos básicos
3. Explicación de los modelos de despliegue
4. Explicación de los modelos de servicio
5. Comparativa de tres proveedores de Cloud services.
6. Aplicaciones sencillas de ejemplo implementando el PaaS de tres proveedores distintos.

## Definición e historia de Cloud Computing
### Definición
_Cloud Computing_ es una tecnología de proceso y manejo de datos, donde los recursos y la capacidad computacional, se proveen al usuario como un servicio de internet. El usuario tiene acceso a sus datos, pero no tiene porque preocuparse por la infraestructura, sistema operativo y el software con el que se trabaja.(Arutyunov, 2012)

Esto es increíblemente útil, ya que un usuario solamente necesita una conexión de internet para poder utilizar un servicio complejo, sin importar el dispositivo que esté utilizando y los recursos del mismo.

Muchas veces el usuario se ve limitado, por que su dispositivo no cumple con los requisitos necesarios para ejecutar una aplicación. Lo cual no es un problema con los servicios de _Cloud Computing_.

### Historia
El fundador de el concepto de _Cloud Computing_ fue John McCarthy, que sugirió en 1960 que en el futuro los cálculos se realizaría a través de servicios públicos. La ideología de _Cloud Computing_, ganó popularidad en el 2007, gracias el desarrollo rápido de canales de comunicación y un aumento en la progresión geométrica de las necesidades de tanto negocios como usuarios particulares para aumentar sus sistemas de información. 

El término como tal se empezó a discutir en el 2008 en una conferencia de internet. Como resultado de estas discusiones, diferentes versiones de _Cloud Computing_ fueron propuestas. Debido a una de estas propuestas, el término «cloud» fue utilizado por primera vez por la cabeza de Google, Eric Schmidt y fue diseminada por los medios de comunicación masivos. Hoy, muchas compañías, por ejemplo, Google, activamente usan el concepto de _Cloud Computing_. Un ejemplo típico es _Google Docs_, que permite trabajar con documentos de oficina, como `.docx` entre otros. (Arutyunov, 2012)

## Conceptos básicos
Cuando se piensa en las diferentes utilidades del cloud computing, se suele pasar por alto un conjunto importante de conceptos que son necesarios para que las aplicaciones en la nube que se utilizan a diario funcionen como suelen hacerlo. Estos, tal vez no se ignoran en su totalidad, más bien se comprende implícitamente al utilizar aplicaciones en la nube, pero es importante abordarlos para identificar cuándo un servicio o implementación consiste de cloud.
### Autoservicio _on-demand_ (bajo demanda)
Consiste en que los usuarios de un servicio pueden acceder a estos por medio de la nube cuando lo necesiten, **sin interacción directa** con el proveedor del servicio. Estos servicios suelen ser completamente de este tipo, porque maximiza el control y la agilidad de los usuarios (Lucidchart Content Team, 2020).
### Red de amplio acceso
Es característico de estos servicios en cloud, no debe confundirse con la definición de una Red de Área Amplia o WAN, pues se refiere a la característica de portabilidad del servicio, es decir, que le dé la capacidad a los usuarios de utilizarlos en diferentes plataformas, donde les sea preferible, como computadores de escritorio, portátiles o dispositivos móviles (Lucidchart Content Team, 2020).
### _Resource pooling_ (puesta en común de recursos)
Es un aspecto muy importante del funcionamiento en la nube. Aborda la escala de distribución de recursos que se le da a la comunidad de usuarios activos, sea almacenamiento, memoria, procesamiento o ancho de banda de red, se le asigna a cada consumidor de estos recursos con base en la demanda que su utilización presente sobre estos. Tiene mucha relación con el siguiente concepto. (Lucidchart Content Team, 2020)
### Rápida elasticidad
En conjunto con la asignación de recursos, esto comprende la agilidad y precisión del sistema para asignar dichos recursos a sus usuarios; es clave que el servicio sea capaz de procesar grandes aumentos o disminuciones en la demanda sin comprometer el servicio ni su calidad. (Lucidchart Content Team, 2020)
## Modelos de despliegue
Los servicios de «nube» pueden ser catalogados en diferentes modelos de despliegue, a continuación se mencionan 3 de estos.
### Privado
La infraestructura de la nube es operada para una organización, incluyendo algunos consumidores, (e.g departamentos en una organización), posiblemente clientes y contratistas. Puede ser manejada por la organización o por un agente externo, y puede 
existir tanto dentro como fuera de la jurisdicción del propietario.(Arutyunov, 2012)
### Público
La infraestructura de la nube es operada para el uso gratuito de un gran rango de usuarios, (“el público”). Una nube pública puede ser propiedad, manejada y operada por una organización comercial, académica o de gobierno( o cualquier combinación de estas que exista). Existe dentro de la jurisdicción del propietario.(Arutyunov, 2012)
### Híbrido
La infraestructura de la nube es operada para el uso gratuito de un gran rango de usuarios, (“el público”). Una nube pública puede ser propiedad, manejada y operada por una organización comercial, académica o de gobierno( o cualquier combinación de estas que exista). Existe dentro de la jurisdicción del propietario.(Arutyunov, 2012)

## Modelos de servicio
También pueden ser catalogados por modelos de servicio, 3 de los más utilizados en la actualidad son:
### _Infrastructure as a Service (IaaS)_
Es la capacidad del consumidor para controlar el procesamiento y el almacenamiento. Por ejemplo, el consumidor puede implementar y ejecutar software arbitrario, que puede incluir sistemas operativos, plataformas y aplicaciones. El consumidor puede controlar los sistemas operativos, el almacenamiento virtual y las aplicaciones implementadas, y tiene un control limitado sobre un conjunto de componentes de red. El proveedor de la nube implementa el control y la gestión de la infraestructura física y virtual principal de las nubes, incluida la red, los servidores, los tipos de sistemas operativos y los sistemas de almacenamiento.
### _Platform as a Service(PaaS)_
Es un modelo en el que los consumidores pueden usar la infraestructura en la nube para la instalación de software base para usar aplicaciones nuevas o previamente existentes (aplicaciones creadas por el consumidor, desarrolladas por pedido o adquiridas). Dichas plataformas incluyen herramientas para la creación, prueba e implementación de software de aplicación, sistemas de gestión de bases de datos, middleware y el entorno de programación que proporciona el proveedor de la nube. El proveedor de la nube realiza el control y la gestión de las principales nubes de infraestructura física y virtual, incluidas las redes, los servidores, los sistemas operativos y el almacenamiento, excepto las aplicaciones desarrolladas o instaladas, así como las configuraciones del entorno de alojamiento de aplicaciones.
### _Software as a Service (SaaS)_
Este se provee al consumidor con el objetivo de usar las aplicaciones del proveedor que pueden ejecutarse en una infraestructura en la nube, que son accesibles desde varios «dispositivos cliente» a través de interfaces simples, como buscadores de internet, un ejemplo de esto siendo cuando se utiliza un browser para acceder al correo electrónico, teniendo en cuenta que todos esos datos se encuentran en la nube. Todos los detalles del control, mantenimiento de la infraestructura física y virtual de este modelo se implementa por el proveedor del servicio.

## Ofertas de mercado
### AWS
![1_b_al7C5p26tbZG4sy-CWqw](https://user-images.githubusercontent.com/36778393/88446521-cab1a280-cde7-11ea-8eb0-7f33323cf606.png)
_Amazon Web Services_ es la oferta de _cloud computing_ de Amazon, fundada en el año 2006, provee servicio cloud bajo demanda tanto a usuarios regulares, como organizaciones. Entre sus servicios destaca el amplio rango de _IaaS_ y _PaaS_ que ofrecen. Esta opción se encuentra entre los primeros puestos de proveedores cloud; tiene beneficios como la alta personalización y las pruebas gratuitas para desarrolladores (de 12 meses), sin embargo cuenta con algunos problemas de servicio al cliente respecto a quejas de otros usuarios (Drake and Turner, 2019).
### Microsoft Azure
![microsoft-azure-1080x675](https://user-images.githubusercontent.com/36778393/88446554-372ca180-cde8-11ea-83ba-646782bbfaca.png)
Este servicio como dice su nombre, es de la empresa Microsoft, que se encuentra entre los grandes de la tecnología actualmente, y es de las mejores ofertas de cloud actualmente. _Azure_ se lanzó en 2010, destaca que sus usuarios pueden ejecutar cualquier servicio en la nube, o combinarlo con aplicaciones existentes, así como centros o infraestructuras de datos. Estos servicios son compatibles tanto con Windows, como Linux, e inclusive se prestan máquinas virtuales en ambos sistemas operativos para la renta. Tiene excelentes pros para los desarrolladores como migración a Azure, para transferir datos a la nube de forma simple, también tiene la ventaja de ser gratuito por doce meses, sin embargo, destacan sus altos precios al terminar las pruebas gratuitas, en comparación con otros proveedores (Drake and Turner, 2019).
### Google Cloud
![oie_616356bDgvYh4s](https://user-images.githubusercontent.com/36778393/88446542-182e0f80-cde8-11ea-9523-30eeeb45e9e7.jpg)
Google no necesita introducción, es empresa lider en la mayoría de campos computacionales actualmente. _Cloud_ es su opción para cloud computing, de este destacan los amplios y modulares servicios que presta principalmente en formatos _IaaS_ y _PaaS_. Sus herramientas se enfocan en el rendimiento y mantenimiento consistente. Algunos ejemplos de sus herramientas son _Cloud Storage_, _Compute Engine_, _Container Engine_, y _Big Query_. Los beneficios más destacados para los desarrolladores son lo amigable para el usuario que son las herramientas y su prueba gratis de 12 meses, aunque algunos comentarios discuten que la configuración de estos servicios pueden ser un poco complicados para principiantes.

## Anexo: justificación de implementación
Se investigó sobre la implementación de código en estas 3 plataformas. Inicialmente, con, AWS y se encontró que  existe una gran variedad de “proyectos” que se pueden realizar, el que más se adapta a los requisitos fue el conocido como _“serverless application”_, despues de seguir una guía de usuario brindada por la plataforma, se pudo elaborar el correspondiente a un "hola mundo", sin embargo, realizar un algoritmo que acepte algún tipo de input resultó ser mucho más complicado, y se encontró con otras complicaciones tanto en esta, como en las otras dos plataformas: habría que poner un dominio a mostrar las aplicaciones por tiepmo indefinido hasta que la investigación se revise.

Con respecto a las otras dos plataformas, se encontró que ni Microsoft Azure o Google cloud proveían un servicio genuinamente gratuito, todos los servicios requerían de una tarjeta de credito para registrarse.

Se exploraron otros dos servicios de Cloud Computing, que pese a ofrecer un rango gratuito, como el servicio de Oracle, o el del IBM, también necesitaban de un dominio web para poder mostrar el funcionamiento del código a terceros, que es algo a lo que no se tiene acceso actualmente. 

## Bibliografía
1. Arutyunov, V. V. (2012). Cloud computing: Its history of development, modern state, and future considerations. Scientific and Technical Information Processing, 39(3), 173-178. Recuperado del artículo código doi:`10.3103/s0147688212030082`
2.  Lucidchart Content Team. (2020, May 15). The Basics of Cloud Computing. Lucidchart. Recuperado de [lucidchart](https://www.lucidchart.com/blog/cloud-computing-basics)
3. Drake, N. and Turner, B., 2019. Best Cloud Computing Services Of 2020: For Digital Transformation. TechRadar. Recuperado de [techradar](https://www.techradar.com/best/best-cloud-computing-services).
