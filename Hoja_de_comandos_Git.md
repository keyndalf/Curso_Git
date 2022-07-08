# Hoja de comandos de Git:

<!-- Cada cambio realizado en un archivo será reconocido por Git -->

## Crear un repositorio:

Se posiciona la consola de comandos en la ruta donde está la carpeta a la que queremos crear un repositorio de Git y usamos el comando:

`git init`

---
## Agregar los archivos al staging area (Árena de preparación) para prepararlos a ser subidos:

Agregar todos los archivos:

`git add .`

Agregar un archivo individualmente:

`git add nombreArchivo`

---
## Hacer un commit:

Después de agregar los archivos con add:

`git commit -m "Descripción del commit"`

Ahora haciendo el commit y el add en una sola instrucción:

`git commit -am "Descripción del commit"`

---
## Mostrar el estado de los archivos:

`git status -s`

---
## Retornar el estado de los archivos hasta un commit anterior:

Ojo: esto regresa todos los archivos hasta un punto previo, así que asegurarse de tener respaldada la información D:

`git reset --hard codigoDelCommit`

---
## Subir un repositorio a Github:

Añadir el repositorio local a Github:

`git remote add origin enlaceDelRepositorio`

---
## Para enviar lo que está en el repositorio local al remoto:

`git push`

---
## Para traer archivos del repositorio remoto al local:

`git pull`

---
## Agregar etiquetas:

Nombre de la etiqueta + -m + Descripción de la etiqueta:

`git tag 08-07-2022v1 -m "Versión 1 del proyecto."`

Subir las etiquetas al repositorio remoto:

`git push --tags`

---
## Clonar un repositorio remoto:

`git clone enlaceCodeDondeEstaElRepositorio`