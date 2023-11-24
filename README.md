# LABORATORIO GIT

## Creación repositorio local

- Crear un directorio y abrirlo con Visual Studio Code.
- Inicializar un repositorio vacío de Git en esa carpeta con el comando "git init".

## Conectarlo con repositorio remoto en GitHub

 - Crear nuevo repositorio remoto vacío en GitHub

 - Poner este comando en la terminal para conectar el repositorio local con el remoto: "git remote add origin https://github.com/mariamoratalla/lemoncode-git.git"

## Primer commit

 - Crear archivo de README.md
 - Añadir los cambios a staged con "git add ."
 - Crear commit con "git commit -m "mensaje""

## Subir la rama main con los cambios al repositorio remoto

Poner en la terminal: git push --set-upstream origin main

## Crear nueva rama llamada development

Poner en la terminal: git branch development

### Cambiar a la nueva rama

Poner en la terminal: git checkout development

## Hacer cambios en la rama nueva y subirlos a GitHub

- Despues de hacer los cambios, escribir "git add ." en la terminal para ponerlos en staged para luego hacer un commit.

- Hacer commit con "git commit -m "mensaje"".

- Subir la nueva rama con sus cambios a GitHub poniendo "git push -u origin development"