# Acordeon GIT
### $ git init
- Inicializa un nuevo repositorio en la carpeta actual
### $ apt-get install git
- Instala git en linux
### $ git --version
- Indica la versión de git
### $git config 
- Configura las variables de git:
- globals : user.name, user.email, core.editor
### $git status
- Muestra el estado acutal del repositorio
### $ git add
- Agrega archivos al repositorio (la bandera -A agrega todos)
### $ git commit
- Registra el estado en la historia del repositorio (la bandera -m para poner una descripción)
### $ git log
- Muestra el historial de commits que se han hecho (la bandera --oneline muestra cada entrada en una sola linea) también se le puede pasar el nombre de un archivo para ver el historial de éste
### .gitignore
- Este archivo permite ignorar archivos o directorios que no queremos que entren en el repositorio. Se pueden usar wildcards)
### $ git checkout
- Permite movernos entre commits o ramas (lleva como argumento el id del commit o parte de el)
### $ git revert
- Hace un revert a un cambio ya registrado creando un nuevo commit (lleva como argumento el id del commit a revertir)
### $ git reset
- Regresa al último estado guardado, borrando permanentemente cualquier cambio en el área de pruebas (lleva la bandera --hard) Borra lo que hemos dado add pero no commit
### $ git clean
- Borra los archivos que no estén en el seguimiento pero estan en la carpeta (lleva la bandera -f para forzarlo)
### $ git branch
-  Crea un branch (si va sin parametros muestra las ramas) si se le pasa el argumento nombre lo utiliza para crear la rama con este nombre
### $ git merge
- Fusiona dos ramas, una rama objetivo con la rama donde nos encontramos (recibe como parámetro la rama objetivo)
### $ git diff
- Muestra las diferencias entre el archivo modificado y la version anterior (antes de hacer el add)