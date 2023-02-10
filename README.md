Paso a paso

Creación del repositorio

> $ "git clone", [Link](https://github.com/giuli-m-muller/devjumpers)。

Creación del archivo Readmi para el repositorio

> $ READMI.md 

Agregar los cambios

> $ git add . 

Guardar los cambios que se hicieron hasta ahora

>  $ commit -m "commit inicial"

Subir los cambios al repositorio

> $ git push

Creación de archivo privado

> $ touch privado.txt

Ahora creo la carpeta privada

> $ mkdir privada

Luego creo el archivo gitignore

> $ touch .gitignore

Git status para ver los archivos

> $ git status

Agrego archivos dentro del gitignore

> $ B echo privada.txt > .gitignore

Creo un archivo 1.txt

> $ touch 1.txt

Creación de la rama v0.2

> $ git branch v0.2

Creo el archivo 2.txt

> $ touch 2.txt

Git status para ver los archivos

> $ git status

Ahora subo los cambios al repositorio

> $ git add . 
> $ git commit -m "agregando fichero 2.txt y nueva rama"
> $ git push

Tuve un mensaje de error

> fatal: The current branch v0.2 has no upstream branch.
>To push the current branch and set the remote as upstream, use

>    git push --set-upstream origin v0.2

>To have this happen automatically for branches without a tracking
>upstream, see 'push.autoSetupRemote' in 'git help config'. 

Se solucióna con el mensaje que se ve en la consola

> $ git branch --unset-upstream origin v0.2

Vuelvo al main

> $ git checkout main

Hago el merge v0.2 en el main

> $ git merge v0.2

Escribo "Hola" en el archivo 1.txt, miro los archivos y agrego los cambios

> $ echo Hola > 1.txt
> $ git status
> $ git add . 
> $ git commit -m "agregue Hola en el archivo 1.txt"

Vuelvo a la rama v0.2 y escribo en el archivo "Adios", reviso los cambios y los guardo

> $ echo Adios > 1.txt
> $ git status
> $ git add . 
> $ git commit -m "Agregue la palabra Adios al archivo 1.txt"

Vuelvo a la rama main y hago merge de v0.2

> $ git checkout main
> $ git merge v0.2

Listo comandos --merged y --no-merged muestran las ramas con y sin merge

> $ git branch --merged
> $ git branch --no-merged

Agrego los cambios, solución de conflictos

> $ git add . 
> $ git commit -m "solucionando conflictos"

Ahora borro la rama v2.0

> $ git branch -d v0.2

Por ultimo escribo el comando para ver ordenado los archivos y los subo al repositorio

> $ git log --oneline --decorate --all --graph
> $ git push

                    
Nombre        | GitHub 
------------- | -------------
María         | <https://github.com/maryjse>
Armando       | <https://github.com/ArmaTQ> 
Diego         | <https://github.com/Dielu85>
Camila Rios   | <https://github.com/camilarios01>
Ivan          | <https://github.com/ivandelaparte>


















