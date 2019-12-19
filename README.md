# Crear alias en Git
Se utilizan para comandos largos que utilices a diario.

Se presenta la siguiente información: 

modificacion desde rama master
como esta esta rama.. 




###### git config --global alias.name-del-alias "comandos a ejecutar"
### git config --global alias.lg "log --oneline --decorate"
Uso:
###### git name  / git lg

# Comandos de Git

### git init
Este comando se usa para crear un nuevo repertorio GIT:

### git add  / git add -A
Este comando puede ser usado para agregar archivos al index.

### git clone
Este comando se usa para crear una copia local funcional del repertorio.

### git commit
El comando commit es usado para cambiar a la cabecera. Ten en cuenta que cualquier cambio comprometido no afectara al repertorio remoto. Usa el comando:
### git commit –m “Message to go with the commit here”
________________________________________________________________________________________________

### git status
Este comando muestra la lista de los archivos que se han cambiado junto con los archivos que están por ser añadidos o comprometidos.

### git push
Este es uno de los comandos más básicos. Un simple push envía los cambios que se han hecho en la rama principal de los repertorios remotos que están asociados con el directorio que está trabajando. Por ejemplo:

#### git push  origin master

__________________
### git checkout
El comando checkout se puede usar para crear ramas o cambiar entre ellas. Por ejemplo, el siguiente comando crea una nueva y se cambia a ella:
### git checkout -b <branch-name>
Para cambiar de una rama a otra solo usa:
  
### git checkout <branch-name>
___________________________________________________
  
### git remote -v
El comando git se usa para conectar a un repositorio remoto. El siguiente comando muestra los repositorios remotos que están configurados actualmente:

### git branch
Este comando se usa para listar, crear o borrar ramas. Para listar todas las ramas se usa:
#### git branch

para borrar la rama:

#### git branch -D <branch-name>
 ____________________________________________
  
### git pull
Para poder fusionar todos los cambios que se han hecho en el repositorio local trabajando.

### git merge
Este comando se usa para fusionar una rama con otra rama activa:
#### git merge <branch-name>
  
### git diff
Este comando se usa para hacer una lista de conflictos. Para poder ver conflictos con el archivo base usa:
#### git diff --base <file-name>
  
El siguiente comando se usa para ver los conflictos que hay entre ramas que están por ser fusionadas para poder fusionarlas sin problemas:

### git diff <source-branch> <target-branch>

### git tag
Etiquetar se usa para marcar commits específicos con asas simples. Por ejemplo:
#### git tag 1.1.0 <instert-commitID-here>
  
### git log
Ejecutar este comando muestra una lista de commits en una rama junto con todos los detalles.

### git reset
Para resetear el index y el directorio que está trabajando al último estado comprometido se usa este comando:
git reset - -hard HEAD

### git rm
Este comando se puede usar para remover archivos del index y del directorio que está trabajando:
git rm filename.txt

### git stash
Este es uno de los comandos menos conocidos, pero ayuda a salvar cambios que no están por ser comprometidos inmediatamente, pero temporalmente:

### git show
Se usa para mostrar información sobre cualquier objeto git.

### git fetch
Este comando le permite al usuario buscar todos los objetos de un repositorio remoto que actualmente no reside en el directorio local que está trabajando.

### git reflog

Historial de los commit.

# Subir los tags

### git push --tags


