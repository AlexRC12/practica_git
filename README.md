# practica_git


¿Qué comando utilizaste en el paso 11? ¿Por qué?
El comando utilizado es: git reset HEAD~1, porque nos permite deshacer los cambios informados en el archivo nuestro.md de staging area a repository.

¿Qué comando o comandos utilizaste en el paso 12?¿Por qué?
El comando utilizado en primera instancia es: git add nuestro.md.
El comando utilizado en segunda instancia es: git commit -m "Rehacer los cambios del último commit nuestro.md rama style",porque al hacer git reset HEAD~1 volvimos a un punto donde los cambios del archivo nuestro.md en la rama style aún no estaban commiteados por eso usamos git add y luego git commit.

El merge del paso 13 ¿Causó algún conflicto?¿Por qué?
No ha causado conflicto porque no se han hecho commit.

El merge del paso 19 ¿Causó algún conflicto?¿Por qué?
Si hubo conflicto, el contenido del archivo nuestro.md de la rama styled y la rama htmlify no contienen la misma información.


El merge del paso 21 ¿Causó algún conflicto?¿Por qué?
No causo conflicto, el contenido del archivo readme.md se actualizó al que contenía styled.


¿Qué comando o comandos utilizaste en el paso 25?
Usé el comando  git log --graph.


El merge del paso 26 ¿Podría ser fast forward? ¿Por qué?
Si podría ser fast forward, porque estamos en la misma rama y tampoco hay commits que se pierdan.

¿Qué comando o comandos utilizaste en el paso 27?
Usé git reset HEAD~1.

¿Qué comando o comandos utilizaste en el paso 28?
Usé git restore nuestro.md.

¿Qué comando o comandos utilizaste en el paso 29?
Usé git branch -D title.

¿Qué comando o comandos utilizaste en el paso 30?
Para rehacer el merge deshecho primero recupero la rama eliminada, en este caso title para ello uso el comando git checkout HEAD@{2} o c23b40a para posicionar el puntero HEAD en la rama donde existia title luego para recuperar la rama uso git branch title.


¿Qué comando o comandos utilizaste en el paso 32?
Usé git reset e05fe17, luego git restore nuestro.md para dejar el archivo como al principio.



¿Qué comando o comandos utilizaste en el paso 33?
Usé git reflog para identificar los commit por los que ha pasado el puntero head.
git  reset HEAD@{2} para ir a la rama donde existia title.
