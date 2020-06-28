# PracticaGitHub

-	¿Qué comando utilizaste en el paso 11? ¿Por qué? 
Utilize el comando git reset – hard HEAD~1 porque quiero deshacer el ultimo commit perdiendo los cambios realizados en el working copy

-	¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué? 

Utilicé los comandos git reflog para el obtener el código del commit, git reset b374f4d y luego git restore git-nuestro.md para rehacer el ultimo commit que acababa de deshacer.

-	El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
Obtuve el mensaje “already up to date” porque el HEAD de la rama en la que se esta fusionando es uno de los padres de la cadena de commits de la rama que se desea fusionar. 

-	El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 
Si se genero conflicto al momento de realizar el merge debido a cambios competitivos en el archivo git-nuestro.md y estos se resolvieron quedándonos con el contenido de la rama “styled”.

-	El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? 
No se genero conflicto alguno porque no hay archivos que estuvieran siendo editados en la misma línea por dos ramas diferentes.

-	¿Qué comando o comandos utilizaste en el paso 25? 
Utilicé el comando git log –graph pues este es el comando utilizado para pintar los grafos en pantalla.

-	El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
El merge si podría ser fast forward debido ambas ramas forman una lista y al momento de realizar el merge fast forward no quedarían commits ‘’No accesibles”.

-	¿Qué comando o comandos utilizaste en el paso 27?
Utilicé los comandos git reset --soft HEAD~1, 

-	¿Qué comando o comandos utilizaste en el paso 28?
Utilicé los comandos git restore --staged git-nuestro.md y git restore git-nuestro.md

-	¿Qué comando o comandos utilizaste en el paso 29?
Utilicé el comando git branch -D title

-	¿Qué comando o comandos utilizaste en el paso 30?
Utilicé el comando git reflog y git reset --hard 000840d

-	¿Qué comando o comandos usaste en el paso 32?
Utilicé el comando git reflog y git reset --hard 7385e6b

-	¿Qué comando o comandos usaste en el punto 33?
Utilicé el comando git reflog y git reset --hard eb92944
