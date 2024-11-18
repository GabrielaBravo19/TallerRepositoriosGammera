Práctica para el aprendizaje de GitHub con el propósito de conseguir una organización más eficaz en nuestros proyectos de Unity.
La plataforma de GitHub ordena toda la información de manera que es posible evitar los fallos humanos.

Para ello en primer lugar debemos crear un repositorio. La interfaz de GitHub permite compartir el proyecto con el resto del equipo,
utilizando el "commit" y el "push". Para recibir un archivo, son necesarios distintos permisos,
además de utilizar la función "pull". Antes de esto, la persona que crea el repositorio debe crear un link
de descarga para que el resto de integrantes pueda clonar (descargar) el repositorio.

Hemos integrado distintas ramas; Scripts,Sound,UI,Player, en cada rama cada uno ha trabajado en una escena distinta sin interferir en la de los demás.
Una vez completados los apartados correspondientes de cada rama, estas se han unificado utilizando la función "merge".
Para el funcionamiento de este método se ha creado la carpeta 
SharedResources; dentro de la carpeta encontramos distintos apartados que recopilan las escenas y otros elementos necesarios para el trabajo de las ramas mencionadas anteriormente.

Para implementar modificaciones o nuevos elementos, por ejemplo agregar un escenario, crearíamos una nueva rama para trabajar dicha tarea sin interferir en las demás,
una vez finalizada la tarea se acoplaría a la rama principal, al entrar a Unity debemos pulsar "reload" para que se puedan visualizar los cambios.
