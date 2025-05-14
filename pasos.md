Paso 1:
Crear un repositorio: git initgit

Paso 2: 
Dar seguimiento a los archivos de nuestro repositorio
agregar git add + el nombre del archivo ej: "index.htmlgit ssa"
para añadir a todos los archivos es "git add ."

Paso 3:
Crear una version (commit) de repositorio
git commit -m "Version 1 de mi repositorio"

con git log podemos ver el listado de commit (versiones)
con git status podemos el estado actualde nuestros repositorios

Paso 4:
Renombra la rama master a main
git branch -M main

Paso 5:
Conectar nuestro repositorio local con un origen remoto
git remote add origin https://github.com/JSoria24/Primer-Repo.git

Paso 6:
Subir nuestros cambios al repositorio remoto
git push -u origin main

PASOS PARA ACTUALIZAR EL PROYECTO
Paso 1:
Añadimos los cambios
Paso 2:
Hacer una version
git commit -m "describir los cambios"
Paso 3:
Subir la version
git push