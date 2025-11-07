#  Comandos de GIT

- `git help`
  Muestra todos los comandos usables en git y muestra informacion general del git como la version <br>
  ![](git%20help.png) 
- `ls`
  Enlista todos los directorios disponibles<br>
  ![](ls.png)
- `git config --global user.name "Tu Nombre"`  
  Define el nombre de usuario global para los commits.<br>
  ![](git%20config%20username.png)
- `git config --global user.email "tu@email.com"`  
  Define el correo electrónico global para los commits.<br>
  ![](git_config_email.png)
- `git config --list`  
  Muestra la configuración actual de Git.<br>
  ![](git_config_list.png)
- `git init`  
  Inicializa un nuevo repositorio Git en el directorio actual.<br>
   ![](git_init.png)
- `git clone https://github.com/johansmith32/ComandosGit.git`  
  Clona un repositorio local.<br>
  ![](git_clone.png)
- `git branch -m "nombre"`
  Renombra la rama en la que esta ubicada la persona<br>
  ![](git_branch_main.png)
- `git status`  
  Muestra el estado de los archivos (modificados, sin seguimiento, etc.).<br>
  ![](git_status.png)
- `git add archivo.txt`  
  Agrega un archivo específico al área de preparación (staging).<br>
  ![](git_add_Archivo.png)
- `git add .`  
  Agrega todos los archivos modificados al área de preparación.<br>
  ![](git_add.png)
- `git reset archivo.txt`  
  Quita un archivo del área de preparación.<br>
  ![](git_reset_archivo.png)
- `git commit -m "Texto commit"`  
  Crea un commit con los archivos en staging y un mensaje descriptivo.<br>
  ![](git_commit_m.png)
- `git log`  
  Muestra el historial de commits creados<br>
  ![](git_log.png)
- `git branch`  
  Lista todas las ramas<br>
  ![](git_branch.png)
- `git branch nueva-rama`  
  Crea una nueva rama<br>
  ![](git_nueva_rama.png)
- `git switch`
  Se ubica en la rama de nombre ingresado<br>
  ![](git_switch.png)
- `git checkout nueva-rama`  
  Se ubica en la rama de nombre ingresado<br>
  ![](git_checkout_rama.png)
- `git checkout -b nueva-rama`  
  Crea una nueva rama y se ubica en esa automaticamente<br>
![](git_check_rama.png)
- `git merge rama-secundaria`  
  Fusiona la rama especificada con la actual.<br>
  ![](git_merge_rama.png)
- `git branch -d rama-secundaria`  
  Elimina una rama local.<br>
  ![](git_delete_rama.png)
  `git add remote URL github`
  Agrega un repositorio remoto<br>
  ![](git_add_remote.png)
- `git remote -v`  
  Muestra los repositorios remotos configurados.<br>
  ![](git_remote.png)

- `git push origin master`  
  Envía tus commits locales a la rama `master` del repositorio remoto.<br>
  ![](git_push_origin_master.png)
- `git pull origin master`  
  Trae y fusiona los cambios del repositorio remoto.<br>
  ![](git_pull_origin_master.png)
- `git fetch`  
  Descarga los cambios del remoto sin fusionarlos.<br>
  ![](git_fetch.png)
- `git diff`  
  Muestra las diferencias entre archivos modificados y el último commit.<br>
  ![](git_diff.png)

- `git show`  
  Muestra detalles de un commit específico.<br>
  ![](git_show.png)