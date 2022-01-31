# Comandos importantes de Git

1. git init
2. git add. 
3. git commit -m "mensaje"
4. git log --oneline "Puedo ver el historial de commit en una sola linea. Nota: Para dejar los commits en pantalla podemos hacer git log --oneline | cat" 
5. git checkout -- .
6. git checkout -b branch-name
7. git branch "Puedo visualizar las ramas del proyecto"
8. git ckeckout branch-name "Te permite navegar entre las ramas del proyecto"
9. git config -- global user.email "email@gmail.com"
10. git config -- global user.name "Name Lastname"
11. git merge branch-name "Operacion de fución entre una rama y la principal"
12. git remote -v  "Para ver el nombre del Repo-remoto actual (origin)"
13. git remote add origin URL "Agregar la URL del Repositorio remoto"
14. git remote set-url origin NEW_URL "Modificar la URL de nuestro Repositorio remoto"
15. git remote rm origin "Nos permite remover el origin remoto"
16. git commit --amend "Este comando nos permtite editar el ultimo commit"
17. git branch -d branch-name "Permite eliminar una rama una vez ya no la necesites"
18. git commit -am "mensaje" - "este comando fuciona el comando git add . y git commit -m"
19. git branch -M nombre_rama_master "Puedo cambiar el nombre de la rama master"
20. git pull origin master "Este comando carga todos los cambios del repositorio remoto en tu repositorio local"
21. git push -u origin master "Este comando carga tu repositorio local master, al repositorio master remoto"
22. git diff --color-words "Este comando nos permite ver las diferencias entre un mismo archivo de diferentes commits"
23. git checkout Commit_ID "Este comando nos permite recuperar alguna versión de nuestro proyecto, escribiendo el ID del commit que queremos recuperar. Tambien se puede asi: git checkout HEAD~1... 2, 3..."
24. git reset ID_COMMIT "Este comando nos permite eliminar o volver a un commit especifico, eliminando los que se encuentren en un nivel superior - Los cambios realizados en el commit o commits eliminados, quedan guardados en el working directory. Para eliminarlos, hay que ejecutar el comando git checkout -- . para cargar los datos del commit actual"
25. git reset --hard ID_COMMIT "La unica diferencia, es que los cambios borrados ya no quedan guardados en el staging area"
26. git reset --soft ID_COMMIT "Los cambios borrados quedan guardados en el staging area"
27. git revert ID_COMMIT "Este comando revierte los cambios realizados en el commit mencionado, creando otro commit nuevo"
