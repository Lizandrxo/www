![](https://itq.edu.ec/wp-content/uploads/2023/02/Recurso-6.png)

                    
Cargo  | Docente  |  |
------------- | -------------
Nombre  | Ing. Sebastián Landázuri  |
Asignatura  | Base de Datos no relacionales    |
Carrera  | Desarollo de Software  | Nivel: Tercer Nivel 
Estudiante  | Bryan Velasco, Alejandro Argoti, Alexis Velasco , Lizandro Duran, Gabriel Salazar    |

--------------Proyecto--------------
=============
##Crear una base de datos no relacionales en MongoDB Compass para saber su funcionalidad:
![](https://fiverr-res.cloudinary.com/images/t_main1,q_auto,f_auto,q_auto,f_auto/gigs/239708679/original/a76d5bfba0311514d6c1f5f607373a1bdd5a865a/anything-and-everything-about-mongodb.png)
###Objetivo

El objetivo principal de este proyecto es diseñar e implementar una base de datos no relacional utilizando MongoDB Compass, estableciendo una conexión eficiente con el cluster de MongoDB Atlas. Se busca comprender y aplicar los conceptos fundamentales de bases de datos no relacionales, aprovechando las capacidades de MongoDB Compass como herramienta gráfica para consultar, optimizar y analizar los datos almacenados. Además, el proyecto tiene como meta explorar y aprovechar las características del servicio de cluster de MongoDB Atlas para garantizar un entorno de base de datos escalable, seguro y de alto rendimiento.

###Marco Teorico

####Bases de Datos No Relacionales:
Las bases de datos no relacionales, también conocidas como bases de datos NoSQL, representan una categoría de sistemas de gestión de bases de datos que difieren del modelo relacional tradicional. Estas bases de datos están diseñadas para manejar grandes volúmenes de datos distribuidos y ofrecen flexibilidad en la estructura de datos, permitiendo almacenar información en formatos como documentos, pares clave-valor, columnares o basados en grafos.

####MongoDB Compass 6.0:
MongoDB Compass es una interfaz gráfica de usuario para MongoDB que proporciona herramientas intuitivas y visuales para interactuar con las bases de datos. Permite realizar consultas, indexar datos, optimizar consultas y visualizar la estructura de la base de datos de manera eficiente. Su capacidad para arrastrar y soltar facilita el desarrollo de consultas y análisis de datos.

####MongoDB Atlas (Cluster) :
MongoDB Atlas es un servicio de base de datos en la nube que proporciona un conjunto integrado de servicios para bases de datos MongoDB. Ofrece opciones de escalabilidad automática, respaldos automáticos, seguridad avanzada y una gestión simplificada. El uso de MongoDB Atlas garantiza una infraestructura confiable y eficiente para la implementación de bases de datos MongoDB en entornos de producción.

####Conexión entre MongoDB Compass y MongoDB Atlas:
La conexión entre MongoDB Compass y MongoDB Atlas se realiza mediante la configuración de las credenciales de acceso y la cadena de conexión específica proporcionada por MongoDB Atlas. Esta conexión segura permite a los usuarios administrar y visualizar los datos almacenados en el cluster de MongoDB Atlas a través de la interfaz gráfica de MongoDB Compass.

####Beneficios de la Implementación:
- Escalabilidad: MongoDB Atlas facilita la escalabilidad horizontal y vertical de la base de datos, permitiendo manejar crecimiento futuro.
- Seguridad: Con MongoDB Atlas, se implementan medidas de seguridad avanzadas, como la autenticación, autorización y cifrado de datos, para proteger la integridad de la información.
- Rendimiento: La optimización de consultas y la distribución eficiente de datos en el cluster contribuyen a un rendimiento óptimo de las operaciones de base de datos.


##Conexion al cluster 
Obtén la URL de conexión: Proporcionada por tu proveedor o clúster, incluyendo detalles como nombre de usuario, contraseña y dirección del servidor.

Configura el controlador de MongoDB: Asegúrate de tener el controlador de MongoDB instalado en tu aplicación, disponible en la mayoría de los lenguajes.

Implementa la conexión en tu aplicación: Utiliza la URL de conexión para establecerla, luego podrás realizar operaciones en la base de datos.



#Proyecto N°2
Nuestro proyecto se basa en hacer una base de datos de Streaming, asi creando una base de datos para una plataforma de streaming con módulos de Contenido Multimedia, Usuarios y Perfiles, y Estadísticas y Análisis, son algunos de los ejemplos que podemos tener dentro de esta base de datos, puedes seguir estos pasos:

Diseño de la Base de Datos:

Contenido Multimedia:
Colecciones: Peliculas, Series, EventosEnVivo.
Campos: Titulo, Descripcion, Duracion, Genero, Actores, Director, AñoLanzamiento, etc.
Usuarios y Perfiles:
Colecciones: Usuarios, Perfiles.
Campos: NombreUsuario, CorreoElectronico, Contraseña, Preferencias, HistorialVisualizacion, ListasReproduccion, etc.
Estadísticas y Análisis:
Colecciones: Visualizaciones, Comentarios, Calificaciones, Tendencias.
Campos: FechaVisualizacion, Usuario, PeliculaSerieEventoID, Comentario, Calificacion, etc.
Conexión a la Base de Datos:

Utiliza el controlador de MongoDB en tu lenguaje de programación preferido.
Conecta tu aplicación a la base de datos utilizando la URL de conexión proporcionada por tu proveedor de MongoDB.


H2 Capturas de las Colecciones
![](https://github.com/Lizandrxo/www/blob/main/Images/MONGODB/Categoria.png?raw=true)
![](https://github.com/Lizandrxo/www/blob/main/Images/MONGODB/Colecciones(1).png?raw=true
)


