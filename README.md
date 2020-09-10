# comandos-git
# la almohadilla funciona como un h1
comandos para entender el git clone de github sin venir de un git init
$ ctrl + shift + v nos permite visualizar la pantalla wysywig al studiocode con el 

git add -agrega archivos al area de trabajo



este tipo de archivos marck down es como se escribe la wikipedia

git commit -es guardar los cambios en un repositorio con el comentario de un add anterior.

git log -muestra la lista de los commit

git commit --amend -permite modificar el último commit sin crear un commit nuevo

git commit -am 'agrega y hace el commit en un archivo que ya está en la zona indizada.'

git commit --amend 'vuelve al commit anterior'


git checkout vuelve al primer commit y en studiocode volvemos a restaurar con ctrl+z

$ git config --global user.name "canodelacuadra"
para cambiar el user.

$ git config --global user.email "canodelacuadra@gmail.com".
///////////////////////



git config --global core.editor "code --wait" -cambia a otro visor como el code y no al nano de bash
Las teclas opcionales están entre paréntesis.

^G      (F1)            Invocar el menú de ayuda

^X      (F2)            Salir de nano

^O      (F3)            Escribir el fichero actual a disco

^R      (F5)            Insertar otro fichero en el actual

^\      (F14)   (M-R)   Reemplazar texto en el editor

^W      (F6)            Buscar un texto en el editor

^Y      (F7)            Moverse a la página anterior

^V      (F8)            Moverse a la página siguiente

^K      (F9)            Cortar la línea actual y guardarla en el cutbuffer

^U      (F10)           Pegar el cutbuffer en la línea actual

^C      (F11)           Mostrar la posición del cursor

^T      (F12)           Invocar el corrector ortográfico (si está disponible)

^P                      Moverse una línea hacia arriba

^N                      Moverse una línea hacia abajo

^F                      Moverse hacia adelante un carácter

^B                      Moverse hacia atrás un carácter

^A                      Moverse al principio de la línea actual

^E                      Moverse al final de la línea actual

^L                      Redibujar la pantalla actual

^^                      Marcar texto en la posición actual del cursor

^D                      Borrar el carácter bajo el cursor

^H                      Borrar el carácter a la izquierda del cursor

^D                      Borrar el carácter bajo el cursor

^H                      Borrar el carácter a la izquierda del cursor

^I                      Insertar un carácter tab

^J      (F4)            Justificar el párrafo actual

^M                      Insertar un retorno de carro en la posición del cursor

^_      (F13)   (M-G)               Ir a un número de línea en concreto

M-C                     Posición del cursor constante habilitar/deshabilitar

M-I                     Auto indentar habilitar/deshabilitar

M-Z                     Suspender habilitar/deshabilitar

M-X                     Modo ayuda habilitar/deshabilitar

M-Z                     Suspender habilitar/deshabilitar

M-X                     Modo ayuda habilitar/deshabilitar

M-P                     Modo Pico habilitar/deshabilitar

M-W                     Auto wrapear habilitar/deshabilitar

M-M                     Soporte para ratón habilitar/deshabilitar

M-K                     Cortar hasta el final de línea habilitar/deshabilitar

M-E                     Expresiones regulares habilitar/deshabilitar

Para más información man nano,   info nano,  /usr/doc/nano   y en la página http://www.nano-editor.org

//////////////////////


Crear un repo git limpio en este directorio:
 $ git init
clone a local/remote git repo (adds the repo referred by branch as a remote named "origin"):
 $ git clone <path>

Mostrar rama actual y archivos con cambios
 $ git status
Mostrar commits anteriores en la rama actual
 $ git log
add changes / new files to the index (single files, "." for the whole dir including subdirs):
 $ git add <path>
commit all changes in the index (to the current branch, asks for commit message):
 $ git commit
commit all changes (even not in the index, but doesn't add new files):
 $ git commit -a
revert all changes made, switch to the last commit (see also other parameters and git checkout):
 $ git reset --hard

create new branch off the current one:
 $ git branch <name of branch to create>
switch current branch:
 $ git checkout <branch to switch to>
delete branch (when all commits in that branch are also in other branches)
 $ git branch -d <branch>
force delete branch (even when commits will be completely deleted by that):
 $ git branch -D <branch>
merge commits of other branch into the current one:
 $ git merge <branch>

add remote repository:
 $ git remote add <name> <path>
pull from remote branch to current branch (merges, remote branch name can be omitted if it has the same name as the local one):
 $ git pull <remote> [branch]
push to remote branch (syntax like git pull, creates a remote branch if non-existant):
 $ git push <remote> [branch]
delete remote branch:
 $ git push :<branch>

See also:
for storing uncommitted changes for later use: git stash
logna


Adrian Julian  11:21
* git add agrega archivos al área de trabajo


 para comentarios con la comilla francesa de al lado de la p.
`` git add .`` 



* git commit guardar los cambios en un repositorio
* git log te muestra la lista de los commits
* git commit -am evita el add
* git commit --amend realizar modificaciones en el ultimo commit sin crear un commit nuevo
* git checkout elimina el ultimo archivo
* git branch muestra las ramas
* git branch nueva-rama
* git checkout nueva-rama
* git merge nueva-rama 'desde la rama master'
* git push origin master 'subimos'
* git remote 'ver los remotos que tenemos'










