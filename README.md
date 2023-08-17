# Git y Github
##Santino Matías Im
![Logo git](/Images/gitlogo.png)


Git es un sistema de control de versiones que permite registrar los cambios realizados a archivos de tu computadora mediante una terminal (Git bash). Git realiza esto mediante repositorios, que fungen como un almacenamiento virtual de tu trabajo
![Logo Github](/Images/githublogo.png)
Github por otra parte, es una plataforma web que nos permite guardar nuestros repositorios de forma remota. Esto con el fin de compartir nuestro proyecto con más personas y darles la capacidad de editarlo y visualizarlo. Lo que permite a múltiples equipos de software aplicar cambios en un mismo proyecto a distancia.
Esto tiene que estar respaldado por medio de llaves electrónicas generadas por SSH (SecureShell), para el traslado seguro de información a traves de Git y Github. Se genera una llave pública y una privada que tienen que coincidir para que el traslado de información sea posible.
[Tutorial SSH](https://experiencia21.tec.mx/courses/388953/files/150007184?module_item_id=25013799)
Para que el trabajo realizado en la terminal local sea visible en la pagina web de Github, se necesita clonar el repositorio web en la computadora. 
Para ello debemos:
1. Crear una carpeta en la computadora (adentro de la carpeta de instalacion de git).
2. Desde la terminal local, entrar a la carpeta recién creada y copiar su ruta.
3. En la terminal, colocar el comando (cd) para cambiar de carpeta en carpeta hasta llegar a la que hemos creado recientemente.
4.  Crear un repositorio en Github y entrar en el
5. Presionar el botón code (<>) y seleccionar la opción SSH para posteriormente copiar el link generado.
6. Escribir el comando git clone en la terminal local y pegar el link que se copió del paso anterior.
7. Colocar yes a la pregunta “Are you sure you want to continue connecting
(yes/no/[fingerprint])?” 
Ya que tenemos sincronizados el repositorio remoto y local en nuestras computadoras, podemos empezar a subir contenido al repositorio remoto (o del remoto al local).
Para realizar esto, se siguen una serie de pasos para que los cambios que un colaborador realice no interfiera con las ediciones que quizá otro colaborador esté haciendo en ese mismo momento. Estos pasos se dividen en:


![Git add, commit, push](/Images/gittutorial.png)

**Git add -A:** En donde se suben los cambios a una zona de revisión para preparar los cambios realizados.
**Git commit -m "Descripción del cambio":** En este paso se  realizan los cambios en el repositorio local.
**Git push origin main:** Se reflejan los cambios realizados en el repositorio local en el remoto (Github).
**Nota:** ¨*Entre cada uno de estos pasos debemos activar el comando **git status** para revisar que todo los cambios que estemos haciendo estén ejecutándose correctamente*
Para realizar este mismo proceso pero de manera inversa (reflejar cambios hechos en el repositorio remoto al local) hacemos:
**Git pull:** Se mueven y reflejan los cambios hechos en el repositorio remoto al repositorio local.


##Referencias

Tecnológico de Monterrey. (s.f) Laboratorio git. Recuperado de https://experiencia21.tec.mx/courses/388953/files/150007184?module_item_id=25013799
Markdown Guide. (s.f) Markdown Cheat Sheet. Recuperado de https://www.markdownguide.org/cheat-sheet/

