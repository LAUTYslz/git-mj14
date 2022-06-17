# GIT Desarrollo Colaborativo

Esto es una guia desarrollada para facilitar la implementacion de la herramienta conocida como GIT, desarrollada por linus Torvalds, y cuya finalidad es el control de versiones de los diferentes proyectos que realizamos.

## Configuracion Inical

Comandos que debemos utilizar tanto para crear un proyecto con git, como para establecer la configutacion de nuestro nombre y correo a utilizar en cada una de las confirmaciones de cambios. El parametro *--global* indica que dicha configuracion aplica para todos los proyectos dek mismo usuario.

* **git init**: inicializa un repositorio en el cual el directorio actual
* **git config --global user.name** `username`: Define de namera global el nombre con el que nos identificamos
* **git config --global user.email** `email`: Define el correo de contacto para las confirmaciones de cambios. 

## Descarga del repositorio
Estos comandos debemos utulizarlos cuando accedemos  un repositorio remoto y necesitamos descargar la info del mismo. Una vez realizada la copia simplemente debemos gestionar los cambios locales y enviarlos, asi como tambien administrar los cambios remotos, para descargarlos e integrarlos al historial local.

* **git clone `remote` `folder`**: descargamos el repositorio remoto en nuestra computadora
* **cd `folder`**: Abrimos el Repositorio clonado tras usar el comando anterior
* **git fetch `renote`**: Solicita el historial de cambios del repositorio remoto.