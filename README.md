# temario-de-App-Web
##Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.  Historia y evolución del desarrollo web:

El desarrollo web comenzó en la década de 1990 con la creación de las primeras páginas web estáticas usando HTML. Con el tiempo, surgieron tecnologías como CSS y JavaScript, permitiendo sitios más interactivos y visualmente atractivos. Posteriormente, el desarrollo web evolucionó hacia aplicaciones dinámicas, impulsadas por lenguajes de servidor como PHP y bases de datos como MySQL. En la actualidad, frameworks modernos y tecnologías como React, Angular, y Node.js permiten la creación de aplicaciones web complejas y escalables.

Tipos de aplicaciones web:
Estáticas: Son páginas cuyo contenido no cambia a menos que el desarrollador modifique el código fuente. Son rápidas y seguras, pero poco flexibles.
Dinámicas: Generan contenido de forma dinámica usando lenguajes del lado del servidor y bases de datos. Permiten interacción con el usuario y personalización.
SPA (Single Page Application): Aplicaciones que cargan una única página HTML y actualizan el contenido dinámicamente mediante JavaScript, mejorando la experiencia de usuario (ejemplo: Gmail).
PWA (Progressive Web App): Aplicaciones web que ofrecen una experiencia similar a una app nativa, incluyendo funcionamiento offline, notificaciones push y acceso desde la pantalla de inicio.
2. Arquitectura de aplicaciones web
Cliente-Servidor:
Modelo clásico donde el cliente (navegador) solicita recursos o servicios al servidor, que procesa las peticiones y responde con los datos solicitados. Permite separar las responsabilidades entre el frontend y el backend.
Arquitectura de tres capas (presentación, lógica, datos):
Divide la aplicación en tres capas:
Presentación: Interfaz de usuario (UI), normalmente gestionada con HTML, CSS y JavaScript.
Lógica de negocio: Procesa la información y gestiona las reglas del sistema, implementada en lenguajes como PHP, Node.js, etc.
Datos: Almacena y gestiona la información, generalmente en bases de datos como MySQL. Esta estructura facilita el mantenimiento, escalabilidad y reutilización del código.
REST y API-first design:
REST (Representational State Transfer): Estilo de arquitectura que utiliza HTTP para interactuar con recursos a través de métodos como GET, POST, PUT y DELETE. Es la base de muchas APIs modernas.
API-first design: Estrategia donde el desarrollo de la API es la prioridad, permitiendo que múltiples clientes (web, móvil, etc.) consuman los mismos servicios. Facilita la colaboración y la integración.
3. Lenguajes y tecnologías fundamentales
HTML (HyperText Markup Language):
Lenguaje de marcado que estructura el contenido de las páginas web (títulos, párrafos, imágenes, enlaces).
CSS (Cascading Style Sheets):
Lenguaje de estilos usado para definir la apariencia visual (colores, fuentes, diseños) de los elementos HTML.
JavaScript:
Lenguaje de programación que permite dotar de interactividad y dinamismo a las páginas web (animaciones, validaciones, peticiones asíncronas).
PHP:
Lenguaje de programación del lado del servidor, ampliamente usado para la creación de aplicaciones web dinámicas y la interacción con bases de datos.
MySQL:
Sistema de gestión de bases de datos relacional, utilizado para almacenar y recuperar información en aplicaciones web.
4. Control de versiones

Git y GitHub:
Git es un sistema de control de versiones distribuido que permite gestionar los cambios en el código fuente a lo largo del tiempo. GitHub es una plataforma basada en Git que facilita la colaboración, el alojamiento de repositorios y la gestión de proyectos de software de forma remota.

Flujo de trabajo con ramas (branching, merge, pull requests):

Branching (ramificación): Crear ramas permite desarrollar nuevas funcionalidades o corregir errores de forma aislada, sin afectar la rama principal.
Merge (fusión): Integrar los cambios de una rama a otra (por ejemplo, de una rama de desarrollo a la principal) para consolidar el trabajo.
Pull requests: Solicitud para revisar e integrar los cambios de una rama en la rama principal, permitiendo discusión, revisión de código y colaboración antes de la fusión final.
<img width="262" height="169" alt="image" src="https://github.com/user-attachments/assets/a0a6ee7e-f0e1-4f7c-af0f-3a9ed5b0af15" />


##Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web  
1. Diseño e implementación del frontend

Maquetación / Wireframe / Mockup:

Maquetación: Es el proceso de estructurar y organizar visualmente los elementos de una página web usando HTML y CSS. Consiste en definir la disposición de menús, botones, imágenes y texto para lograr una interfaz coherente y funcional.
Wireframe: Esquema básico y simplificado de una página web, que muestra la estructura y organización de la interfaz sin detalles visuales. Suele realizarse en blanco y negro y sirve como guía inicial para el diseño.
Mockup: Representación visual más detallada y realista del diseño final. Incluye colores, tipografía, imágenes y otros elementos gráficos. Permite visualizar cómo se verá la interfaz antes de implementarla.
API:
Es un conjunto de reglas y especificaciones que permite que el frontend se comunique con servicios externos o el backend. En el contexto web, el frontend suele consumir APIs REST para obtener o enviar datos, usando tecnologías como Fetch o Axios en JavaScript.

2. Diseño e implementación del backend

Servidor:
Es el componente que recibe las peticiones de los clientes (usuarios) y responde procesando la lógica de negocio, gestionando la autenticación, validaciones y acceso a la base de datos. Puede estar desarrollado en lenguajes como Node.js, PHP, Python, Java, etc.

Manejo de peticiones y respuestas HTTP:
El backend gestiona las solicitudes del cliente mediante el protocolo HTTP. Interpreta métodos como GET (obtener datos), POST (crear datos), PUT/PATCH (actualizar datos) y DELETE (eliminar datos), y responde con información, mensajes de error o confirmaciones.

Conexión a bases de datos (MySQL, PostgreSQL, MongoDB):
El backend se conecta a sistemas de gestión de bases de datos para almacenar, consultar y modificar información.

MySQL y PostgreSQL: Bases de datos relacionales, ideales para datos estructurados y relaciones complejas.
MongoDB: Base de datos NoSQL orientada a documentos, flexible para datos no estructurados.
3. Bases de datos

Modelado de datos y relaciones:
Es el proceso de definir las entidades, atributos y relaciones entre los datos que almacenará la aplicación. Incluye la creación de diagramas y esquemas para organizar la información de manera eficiente y lógica.

ORM (Object Relational Mapping):
Es una técnica o herramienta que permite mapear objetos del código (clases) a tablas de bases de datos, facilitando la interacción y abstrayendo el uso de SQL. Ejemplos incluyen Sequelize (Node.js), Doctrine (PHP), y Hibernate (Java).

CRUD desde el backend:
CRUD son las operaciones básicas para gestionar datos: Crear (Create), Leer (Read), Actualizar (Update), y Eliminar (Delete). El backend implementa estas operaciones para interactuar con la base de datos, normalmente a través de rutas o endpoints de una API.

4. Seguridad básica en aplicaciones web

Validación de formularios:
Es el proceso de verificar que los datos enviados por el usuario cumplen con los formatos y restricciones requeridos antes de ser procesados por el backend. Esto previene errores y ataques como la inyección de código.

Autenticación y autorización:

Autenticación: Proceso para verificar la identidad de un usuario (por ejemplo, mediante usuario y contraseña).
Autorización: Proceso que determina los permisos o acciones que un usuario autenticado puede realizar dentro del sistema, asegurando que solo acceda a recursos para los que tiene permiso.

<img width="308" height="143" alt="image" src="https://github.com/user-attachments/assets/616bf72f-b770-4ffb-886d-18e8393b3ae4" />


##Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional
1. Integración de frontend y backend
Interfaz de usuario Frontend:
Es la capa visual con la que interactúa el usuario en una aplicación web. Consiste en páginas, formularios, botones, menús y otros elementos diseñados usando HTML, CSS y JavaScript (o frameworks modernos como React, Vue o Angular). Su objetivo es ofrecer una experiencia intuitiva y atractiva.

Manejo de API:
El frontend se comunica con el backend mediante APIs, generalmente a través de peticiones HTTP (por ejemplo, usando fetch o axios). El API define los puntos de acceso (endpoints) y los datos que se pueden consultar o modificar, permitiendo así que la interfaz muestre información dinámica y actualizada.

Proceso de Solicitud y Respuesta de Backend:
Cuando el usuario realiza una acción (como enviar un formulario), el frontend envía una solicitud al backend. El backend procesa la petición (por ejemplo, consultando o modificando la base de datos), y responde con un resultado (datos, confirmación, error, etc.), que el frontend utiliza para actualizar la interfaz.

2. Almacenamiento en Servidor
Tipos de servidores:
Un servidor es una computadora o software que atiende peticiones de clientes. Puede ser:

Servidor físico: Máquina dedicada exclusivamente a servir aplicaciones.
Servidor virtual (VPS): Una partición virtualizada dentro de un servidor físico.
Servidor en la nube: Recursos flexibles y escalables ofrecidos por plataformas como AWS, Azure o Google Cloud.
Servidores y servicios de hosting:
El hosting es el servicio que proporciona espacio y recursos en un servidor para alojar aplicaciones web. Existen diferentes tipos:

Hosting compartido: Varios sitios comparten los recursos del mismo servidor.
VPS: Recursos dedicados en un entorno virtualizado.
Hosting dedicado: Un servidor completo para un solo cliente.
Cloud hosting: Recursos dinámicos y escalables en la nube.
Proveedores de Servicios de Almacenamiento:
Empresas y plataformas que ofrecen almacenamiento y alojamiento de aplicaciones, como:

Amazon Web Services (AWS)
Google Cloud Platform (GCP)
Microsoft Azure
Heroku
Vercel, Netlify (para apps estáticas/frontends)
DigitalOcean
3. Optimización y rendimiento
Optimización de recursos (imágenes, scripts):
Se refiere a reducir el tamaño y la cantidad de archivos que la aplicación envía al navegador para mejorar la velocidad de carga. Ejemplos:

Comprimir imágenes y elegir formatos adecuados (WebP, JPEG optimizado).
Minimizar y comprimir archivos JavaScript y CSS.
Cargar scripts de forma asíncrona o cuando sean necesarios (lazy loading).
Utilizar cachés para evitar transferencias repetidas.
Despliegue de aplicaciones web:
Consiste en publicar la aplicación en un servidor o plataforma para que los usuarios puedan acceder a ella. Incluye:

Subir archivos y código al servidor.
Configurar servicios necesarios (base de datos, variables de entorno).
Verificar que funcione correctamente en el entorno de producción.
CI/CD básico (Integración y Despliegue Continuos):
CI/CD son prácticas que automatizan la integración, prueba y despliegue de aplicaciones:

CI (Continuous Integration): Automatiza la integración y pruebas del código, detectando errores rápidamente.
CD (Continuous Delivery/Deployment): Automatiza la publicación de nuevas versiones de la aplicación, facilitando actualizaciones frecuentes y confiables.
Documentación del proyecto:
Consiste en crear y mantener documentos que expliquen el funcionamiento, instalación, uso y mantenimiento de la aplicación. Incluye guías para desarrolladores y usuarios, ejemplos de uso, requisitos, y referencias de la API.
<img width="294" height="162" alt="image" src="https://github.com/user-attachments/assets/a3479d37-db55-46e7-81e3-f1067e5b5328" />


