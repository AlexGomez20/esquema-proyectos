El proyecto
===========

Descripción General
-------------------

El proyecto consiste en una aplicación web, que consiste en un lugar donde
se podrán visualizar los diferentes eventos creados, además de tener un espacio para que los
artistas se puedan registrar, y así crear un directorio digital, donde las personas podrán
contactar a los artistas, cabe mencionar que los artistas también podrán crear eventos.

El cliente solicitó el software ya que presentaba ciertos problemas a la hora de
querer contactar con un artista, además de no tener un lugar digital donde publicar
los eventos, con estos problemas se solicitó un software que ayude a la institución
a mejorar estos procesos.

Los que van a manejar este software serán los administradores de la casa de la cultura.


Los módulos principales son:

* Usuario
* Evento
* Directorio
* Estadísticas
* Notificaciones


Módulos
^^^^^^^




Usuario
++++++++
Se encarga de manejar toda la información del :ref:`referencia-a`, así como el tipo de usuario que es,
también sus privilegios que tiene, este módulo maneja el perfil del usuario,
y sus diferentes acciones que este podrá manejar,
en este caso se tendrán tres tipos de usuarios que pertenecen a diferentes
áreas que son: comunicaciones, secretaría y administradores,
en este módulo llegaran las solicitudes de autorización de cada artista que se requiera registrar,
y los administradores van a poder verificar la información, para dar autorización de los artistas.
Este módulo se encargará de:

- Creación de usuario: En la creación de usuario se tomara toda la información del usuario a registrarse
  la información del usuario será:

  + Nombre
  + Apellido
  + Tipo de contacto (Teléfono o Correo)
  + Direccion
  + Descripcion
  + Contrasenia
  + Imagen

- Modificación de usuario En esta parte se podrán editar los datos ingresados, ya sea su contraseña,
o algún dato como teléfono o correo.

- Recuperar contraseña: Como cada usuario tiene una contraseña, si esta se extravió, esta parte es la que
le corresponde a recuperar dicha contraseña, mandandole un mensaje por el tipo de contacto que tenga.

- Autorización de artista: Si el usuario es del tipo administrador aquí va a poder autorizar al artista
que se requiera registrar, después de comprobar los datos, llega una notificación al administrador, que se
encargará de autorizarlo.

Evento
+++++++
Lo que se refiere a :ref:`referencia-b` es el que se encarga de gestionar los diferentes eventos,
en este módulo se manejara la creación de cada evento,
si son los usuarios se podrá especificar el nivel de impacto que estos tendrá,
un artista también va a poder crear los eventos,
los usuarios también podrán modificar el nivel de impacto que tendrá el evento del artista,
en este módulo los visitantes y artistas podrán dejar una reseña de cómo estuvo el evento,
además que el lenguaje no va a estar restringido.
Resumiendo lo que hará este módulo es:

- Creación de eventos: La creación de eventos no es más que pedir que datos serán visibles,
  en el evento, como:

  + Nombre
  + Fecha
  + Dirección
  + Categoría
  + Imagen
  + Nivel de impacto (Solo administradores)

Como se puede observar el evento también tendrá una imagen, el cual es el que se va a mostrar
en la pantalla principal, si el usuario o el artista requiera subir una imagen esta es la que se
mostrará.

- Modificación de eventos: Se permitirá modificar cierta información del evento, como su
nombre, fecha, imagen.

- Reseñas de evento: Cada evento tendrá un espacio para que los visitantes se puedan comunicar o
expresar sus pensamientos de dicho evento, en esta parte no se tendrá ninguna restricción de lenguaje
, pero si se necesitara que proporcionen un nombre o correo.


Directorio
+++++++++++
La parte de :ref:`referencia-c` contendrá a todos los artistas,
los artistas van aparecer con un diseño tipo cartelera,
además que se podrá buscar por artistas,
así como sus diferentes filtros,
como la categoría o el tipo de artista,
además en cada artista se pondrá su información básica y
un lugar donde se para que se puedan contactar con dicho artista,
además de que habrá también instituciones que fomente la cultura.
Este módulo se encarga de:

- Visualización de artistas: La visualización no es mas que la recopilación de los datos
  de los artistas o de instituciones registradas, lo que mostrara son los datos más relevantes,
  como:

  + Nombre  (Artista o institución)
  + Categoría (Músico, Dibujante, etc)
  + Eventos (Eventos organizados recientemente o en los que estuvo presente)
  + Botón de contacto.

- Búsqueda de artista: La parte de la búsqueda va a estar definida por distintos filtros,
como artistas más solicitado, también por categorías, además del filtro por orden alfabético,
para que se pueda buscar de forma más eficiente.

Estadísticas
+++++++++++++
Las :ref:`referencia-d` son una parte importante del proyecto, ya que
están se van a encargar mostrar la diversa información que se ha guardado,
aquí se expondrá quienes son los artistas más contactados por un tiempo definido,
además de que se podrá hacer un consenso de que tipos de artistas son los que más se registran.
Este módulo se encarga de:

- Estadísticas de información: las estadísticas se van a mostrar de acuerdo a los
  siguientes criterios:

  + Eventos más visitados
  + Artistas mas contactados
  + Eventos más creados por categorías
  + Mayor cantidad de artistas por categoría
  + Eventos más comentados

Notificaciones
+++++++++++++++
En las :ref:`referencia-e` se manejan las cápsulas educativas,
una cápsula educativa contendrá un tipo de dato histórico,
esto contendrá un límite de 255 caracteres, p
ara que la cápsula no sea muy cargada de información y sea más fácil de leer.
Este módulo se encarga de:

- Creación de cápsula educativa: Esta parte se encarga de tomar toda la información de la
  cápsula, la información que se va a pedir es:

  + Fecha (Fecha en que se va a publicar)
  + Nombre (Título de la cápsula)
  + Contenido

- Modificar Cápsula: Si algún dato de una cápsula está mal, o esta mal redactado, se podrá modificar
la información de dicha cápsula.

- Restricción de 255 caracteres por contenido de cápsula.
