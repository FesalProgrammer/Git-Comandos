# Comandos de Git utiles
1. git init (inicia el control de version del repositorio)
2. git add . (agrega todos los archivos y los eleva al stage )
3. git reset . (revierte el add, te baja del stage)
4. git commit -m "msj descriptivo" (salva los cambios y crea el numero del commit)
5. git checkout -- .(Restaura el repositorio al estado del ultimo commit, muy util para aquellos casos donde el codigo se rompe).
6. git log (genera el historial de commits). usar la letra q para salir.
7. git commit --amend (util para editar el texto del msj del commit).
8. para salir de git --amend ingresar la letra "q".
9. ejemplo msj mal escrito q necesita edicion. despues de la instruccion git commit --amend hacer click en ins(tecla 0), editar el texto y despues para salir de alli, hacer click en esc luego escribir :wq!
10. git checkout master (se usa para viajar desde una rama a la rama master)
11. git checkout -b rama-contact
12. Estos 3 comandos se pueden insertar en un unico enter. Aqui enviamos nuestro repositorio local a GitHub. Antes hay que crear el repositorio en GitHub, es decir, dar un nombre al repositorio, GitHub acepta el mismo nombre de la carpeta local o un nombre diferente, no pasa nada.
    git remote add origin https://github.com/FesalProgrammer/Git-Comandos.git
    git branch -M main
    git push -u origin main (solo la 1era vez se escribe completo)
13. git branch -d rama-contact
14. git push (sirve para enviar lo commiteado a GitHub (actualiza tu repositorio en la nube) y despues de la 1era vez no es necesario escribir  -u origin main )
