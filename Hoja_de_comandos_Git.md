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

---
## Crear una rama:

`git branch NombreRama`

---
## Como ver las ramas disponibles:

`git branch`

---
## Como cambiar de rama:

Notar que los cambios hechos en una rama no se ven reflejados en las distintas ramas, solo podemos ver el estado de los archivos al momento de la creación de la rama, a menos que se actualice la información haciendo una unión de ramas:

`git checkout NombreRama`

---
## Unir ramas:

Este proceso se debe hacer desde la rama principal:

`git merge NombreRamaQueQuieroUnir`

---
## Eliminar una rama:

`git branch -d NombreRama`

<!-- Agrego un comentario desde el branch rama-->

<!-- Me encargo de añadir información a la hoja de comandos desde la rama keyber, veremos si somos capaces de hacer un merge desde la rama keyber -->

---
## Crear una copia en Github (fork) para posteriormente hacer una copia local:

El pull request sirve para crear una copia en Github de u repositorio público, cosa que podemos hacer nuestros propios commits y si en un futuro queremos sugerir cambios al proyecto podemos hacer las sugerencias con un pull request.

El fork se puede hacer desde la misma página de Github.

El pull request también se hace desde github.
