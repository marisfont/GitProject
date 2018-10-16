Proyecto 1
## Paso 1
>Crear carpeta "Git Project" en la terminal usando mkdir
## Paso 2
>Crear archivo "README.md" en la terminal usando touch
## Paso 3
>Crear repositorio local usando git init
## Paso 4
>Ingresar a GitHub para crear proyecto "GitProject" 
>Usar las intrucciones paso a paso para enlasar el repositorio local con en linea
## Paso 5
>Crear branch "rama1" usando git checkout -b "rama1". 
>Confirmar que se creo la rama usando git branch.
## Paso 6
>Crear un documento python "Conflict.py"
>incluir lo siguiente print("this is the original message")
## Paso 7
>Crear branch "ramaconflict" usando git checkout -b "ramaconflict".
>Confirmar que se creo la rama usando git branch.
## Paso 8
>Editar el codigo en "Conflict.py" usando la rama "ramaconflict"
>print("this is the altered message")
>Commit y push los cambios a la rama "conflict"
## Paso 9
>Moverse a al master branch usando git checkout master
>Hacer merge entre la rama "master" y la rama "conflict" usando git merge conflict
## Paso 10
>Editar el codigo en "Conflict.py" usando la rama "master"
>print("this is the master message")
>Commit y push los cambios a la rama "master"
## Paso 11 
### ERROR
>Hacer merge entre la rama "master" y la rama "conflict" usando git merge conflict
>Obtenemos un error 