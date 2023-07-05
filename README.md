# actividadGit

sistemas <br><br> 
operativos

_21/06/23_

_**Actividad Git**_

**Respuestas :** 

**1)-**

_a)- Git es un sistema de control de versiones distribuido, lo que significa que un clon local del proyecto es un repositorio de control de versiones completo. Estos repositorios locales plenamente funcionales permiten trabajar sin conexión o de forma remota con facilidad. ~~Los desarrolladores confirman su trabajo localmente y, a continuación~~ , sincronizan su copia del repositorio con la copia en el servidor. Este paradigma es distinto del control de versiones centralizado, donde los clientes deben sincronizar el código con un servidor antes de crear nuevas versiones._
La flexibilidad y popularidad de Git hacen que sea una excelente opción para cualquier equipo. Muchos desarrolladores y graduados universitarios ya saben cómo usar Git. La comunidad de usuarios de Git ha creado recursos para entrenar a desarrolladores y la popularidad de Git **facilita** la ayuda cuando sea necesario. Casi todos los entornos de desarrollo tienen **compatibilidad** con Git y las herramientas de línea de comandos de Git implementadas en cada sistema operativo principal.

_b)- Cada vez que se guarda el trabajo, Git crea una confirmación. Una confirmación es una instantánea de todos los archivos en un momento dado. Si un archivo no ha cambiado de una confirmación a la siguiente, Git usa el archivo almacenado anteriormente. Este diseño difiere de otros sistemas que almacenan una versión inicial de un archivo y mantienen un registro de deltas a lo largo del tiempo._

_Las confirmaciones crean vínculos a otras confirmaciones, formando un gráfico del historial de desarrollo. Es posible revertir el código a una confirmación anterior, inspeccionar cómo cambiaron los archivos de una confirmación a la siguiente y revisar información como dónde y cuándo se realizaron los cambios. Las confirmaciones se **identifican** en Git mediante un hash criptográfico único del contenido de la confirmación. Dado que todo está hash, es imposible realizar cambios, perder información o archivos dañados sin que Git lo detecte.
Ramas
Cada desarrollador guarda los cambios en su propio repositorio de código local. Como resultado, puede haber muchos cambios diferentes en función de la misma confirmación. Git proporciona herramientas para aislar los cambios y volver a **combinarlos** posteriormente. Las ramas, que son punteros ligeros para trabajar en curso, **administran esta separación.** Una vez finalizado el trabajo creado en una rama, se puede combinar de nuevo en la rama principal (o troncal) del equipo._

