# deleon_juan
Juan de leon garcia
link: https://github.com/Juandeleongarcia/deleon_juan.git 
1) Se puede enviar un pull and request desde una cuenta a otra para poder copiar el repositorio que se ha mandado en esa cuenta y poder ver y depende de los permisos de la
    cuenta editar. Para poder hacer el PR has de enviar una solicitud a la cuenta a la que quieres enciar el trabajo, desde esa cuenta se acepta y ya tienes el repositorio
    en la cuenta.
2) Un merge conflict se produce cuando realizamos un merge y hay diferencias entre lo que queremos fusionar. Esto se puede solucionar con el editor de texto, editando lo que
   se ha repetido o no interesa tener ya que hace que el merge falle.
3) Para fusionar dos ramas debemos escribir el comando git merge -m integrar "examen_parcial y main" main, si las ramas son mergeables se realizara el merge.
4) Para revertir el ultimo commit y regresar al proyecto anterior debemos meter el comando git reset --soft HEAD-1 (esto borra unicamente el ultimo commit).
5) Cuando entras en un repositorio en gitHub puedes darle al fork y te creara una copia del repositorio en tu cuenta, a partir de ahi puedes modificar y añadir cosas que no
   afectara al original ya que es otro aparte. Sin embargo, el dueño del repositorio forkeado podra ver quien ha realizado fok y que cambios han realizado en el mientras este
   actualizado en gitHub.
6) a) Para llegar directamente al directorio en el que se encuentra el "archivo.txt" realizaria el comando, cd UAX/Universidad/Nombre_del_alumno. Este tipo de ruta seria una
   ruta absoluta.
   b) Para llegar al directorio desde "Universidad" usariamos el comando, cd Nombre_del_alumno. Esto seria una ruta relativa.
7) 1) b) git clone
   2) a) git branch
   3) c) git checkout
   4) b) git add
   5) b) git commit
   6) b) git push
   7) a) git push
   8) d) git merge
   9) a) git reset -hard
   10) c) git log
8) Primero integraria las ramas de matematicas y develop con el comando, git merge -m integrar "matematicas y develop". Esto podria tener conflictos que tendriamos que
   solucionar con el editor de texto. Entramos en el editor y nos aseguramos de que se mantiene la calidad del codigo y que no haya ningun error. A continuacion integraria
   la rama Diseño UX con develop con el comando, git merge -m integrar "Diseño UX y develop", me volveria a asegurar de que no hayan conflictos y si los hubiera
   solucionarlos. Ahora ya tendriamos las dos ramas integradas en la rama develop y listas. 
10) c) Añadiste el botón "x^4" al archivo "index.html" en tu repositorio local, creaste un commit con los cambios y luego subiste el repositorio local al remoto en
    la rama principal (master).
   
