El proyecto
===========

Descripción General
-------------------

El software que se implementara tendrá como función llevar a cabo la administración de
Los artistas que se encuentren registrados como los eventos que se realicen, ya sean
internos o externos.

Dentro del software se podrán registrar artistas, dentro de esa opción se ingresaran
los datos del mismo y como contactarlo, después de llenar el formulario se esperara a
la aceptación de este por parte del administrador. Esta información podrá ser vista
por todo el público para que puedan saber sobre el artista.

También contara con una parte de eventos en la cual si se es un artista se pobra
crear un evento pero este tendrá que ser validado primero por el administrador para
poder llevarse a cabo, si no se es un artista se podrá ver que eventos se realizaran y
además se podrán ver por categorías, por ejemplo: concierto de blues.

Además contara con una sección informativa en la cual un administrador ira agregando
información que crea conveniente en fechas específicas, con el fin de informar a las
personas para que sepan más sobre su cultura.

Con los datos recolectados de los artistas y eventos se podrán generar estadísticas
que ayuden a los altos mandos para tomar decisiones sobre qué actividades son las mas
aceptadas o que artistas prefieren, estas estadísticas también podrán ser vistas por
otros trabajadores siempre y cuando tengan la autorización de su superior.


Modulos
^^^^^^^

Artistas
^^^^^^^^
Este modulo contara con las funciones tales como registro de artistas, en el cual
al registrarse se necesitara la confirmación del administrador para poder ser aceptado.

Si se desea ingresar como un artista será necesario que realice un login en el sistema.

Si no ingresa al modulo para registrarse podrán realizar las acciones como: ver a todos los
artistas o buscar a un artista especifico, al ingresar en su perfil el sistema le mostrara
la información básica de este y la forma de contactarlo.

Diagrama de caso de uso: :ref:`referencia-a`.

Eventos
^^^^^^^
Con este módulo se podrán crear eventos pero también será necesaria la confirmación de
un administrador, tanto artistas como visitantes podrán ver o buscar los eventos ya planificados,
la forma de búsqueda puede ser por categorías, ejemplo: música, dibujo entre otros.

Los eventos podrán ser puntuados por los visitantes, además de esto se podrá visualizar y
agregar comentarios.

Diagrama de caso de uso :ref:`referencia-e`.

Espacio Informativo
^^^^^^^^^^^^^^^^^^^
El administrador del sistema podrá agregar información cultural relevante en una fecha, esta
se encontrara visible tanto para visitantes como para artistas.

Diagrama de caso de uso: :ref:`referencia-i`.

Administración
^^^^^^^^^^^^^^
El encargado podrá confirmar la creación de artistas o eventos.

Se podrán gestionar a los artistas, eventos y los espacios informativos, esto quiere
decir que podrá eliminar artistas, eventos o espacios informativos.

Se podrán generar estadísticas sobre los artistas o eventos, esta información esta dirigirá
a los altos mandos, estas estadísticas estarán centradas en mostrar la aceptación de los eventos,
además los colaboradores de menor jerarquía podrán tener acceso a estas mediante un permiso de su superior.

Diagrama de caso de uso: :ref:`referencia-ad`.
