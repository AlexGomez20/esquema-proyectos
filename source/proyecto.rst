El proyecto
===========

Descripción General
-------------------

El software a desarrollar es una aplicación web dispuesta a brindar un espacio a nuestro cliente, un lugar donde se pueda promover la cultura a través de eventos, más un espacio para que los artistas se puedan dar a conocer, los artistas deberán de tener un tipo de contacto para que se pueda registrar este contacto lo verificaran los administradores para que se le de autorización, esto se hace para evitar información falsa, una vez autorizados los artistas ya podrán aparecer en la agenda, en el perfil del artista se va a tener la opción de contactarlo, esto se hace para ir guardando la información de que cantidad de gente contacta al artista, el artista también va a poder crear sus propios eventos, en los eventos se tendrá la opción de agregar reseñas, en el cual las personas se podrán expresar abiertamente sin restricción, los eventos principales que irán apareciendo en la página principal se va a medir por el nivel de impacto que se tiene, también se requerirá notificar una capsula educativa que solo tendrá 255 caracteres, y esta deberá cambiar cada día, la información adquirida dará al cliente estadísticas para la tomas de decisiones, esta aplicación va a estar diseña para que se pueda expandir más en el futuro si el cliente lo desea.
Los módulos principales son:

* Usuario
* Artista
* Evento
* Directorio
* Estadísticas
* Notificaciones


Modulos
^^^^^^^

Usuario
+++++++++
En este módulo se tomara los datos del usuario, como el tipo de usuario que es, así como los privilegios que estos tienen, este módulo manejara el perfil del usuario, y sus diferentes acciones que este podrá manejar, en este caso se tendrán tres tipos de usuarios que pertenecen a diferentes áreas que son: comunicaciones, secretaria y administradores, en este módulo llegaran las solicitudes de autorización de cada artista que se requiera registrar, y los administradores van a poder verificar la información, para dar autorización de los artistas."
Este modulo se encargara de:

- Creacion de usuario
- Privilegios de usuario
- Modificacion de usuario
- Autorizacion de artista

Artista
++++++++++++
Este modulo es donde se va a desarrollar lo que es la total gestion a lo
que se refiere artista, lo que va a ser este modulo es:

- Creacion de artistas
- Modificacion de perfil artista
- Artista cree eventos

**Creacion de artistas**:  Esta parte es donde se va a recibir la informacion del artista, para que se pueda crear su perfil, una parte obligatorio en esta para que el artista pueda aparecer en el directorio tendra que esperar la autorizacion del administrador.

**Modificacion de perfil artista**: Esta parte es donde se podra modificar la informacion del artista basica, asi como su imagen, tipo de contacto.

**Creacion eventos artista**: Este parte es donde el artista podra crear su evento.


Evento
+++++++
Este módulo se encarga de gestionar los diferentes eventos,
en este módulo se manejara la creación de cada evento,
si son los usuarios se podrá especificar el nivel de impacto que estos tendrá,
un artista también va a poder crear los eventos,
los usuarios también podrán modificar el nivel de impacto que tendrá el evento del artista,
en este módulo los visitantes u artistas podrán dejar una reseña de como estuvo el evento,
además que el lenguaje no va a estar restringido.
Resumiendo lo que hara este modulo es:

- Creacion de eventos
- Modificacion de eventos
- Reseñas de evento


Directorio
+++++++++++
Este módulo contendrá a todos los artistas,
los artistas van aparecer con un diseño tipo cartelera,
además que se podrá buscar por artistas,
así como sus diferentes filtros,
como la categoría o el tipo de artista,
además en cada artista se pondrá su información básica y
un lugar donde se para que se puedan contactar con dicho artista,
además de que habrá también instituciones que fomente la cultura.
Este modulo se encarga de:

- Visualizacion de artistas
- Filtros sobre busqueda de artista o institucion

Estadísticas
+++++++++++++
Este módulo se encarga de mostrar
las estadísticas de la diversa información que se ha guardado,
aquí se expondrá quienes son los artistas más contactados por un tiempo definido,
además de que se podrá hacer un consenso de que tipos de artistas son los que más se registran.
Este modulo se encarga de:

- Estadisticas de informacion

Notificaciones
+++++++++++++++
En las notificaciones se manejaran las capsulas educativas, una capsula educativa contendrá un tipo de dato histórico, esto contendrá un límite de 255 caracteres, para que la capsula no sea muy cargada de información y sea más fácil de leer."
Este modulo se encarga de:

- Creacion de capsula educativa.
- Modificar Capsula
- Restriccion de caracteres maximo en cada capsula.
