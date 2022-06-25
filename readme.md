# Respuestas al ejercicio 1

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
$git reset --hard HEAD~1	*reset para deshacer el ultimo commit, --hard para deshacer incluso lo que hay en el working copy, y HEAD~1 para indicarle volver al commit padre*

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
$git reflog			*para ver logs y saber SHA de ultima referencia*
$git reset --hard 64a0fe3	*para rehacer los cambios en working copy*

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
$git merge master		*No causó conflicto porque no hubos cambios en commits*

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
$git merge htmlify		*No, al no haber cambios en las versiones del archivo en cada rama*

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
$git merge styled. 		*No, al no haber commits que no tenga ya la rama master*

- ¿Qué comando o comandos utilizaste en el paso 25?
$git log --graph		*También se podia haber añadido --pretty para mostrarlo mas resumido*

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
$git merge --no-ff title	*No , porque saltaria conflicto al haber cambios en git-nuestro.md al no saber cual es la version buena*

- ¿Qué comando o comandos utilizaste en el paso 27?
$git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?
$git reflog			*Para saber el SHA al que debo moverme*
$git reset a091fce

- ¿Qué comando o comandos utilizaste en el paso 29?
$git branch -d title

- ¿Qué comando o comandos utilizaste en el paso 30?
$git reflog			*Para saber el SHA al que debo moverme*
&git reset a091fce

- ¿Qué comando o comandos usaste en el paso 32?
$git reflog
$git reset

- ¿Qué comando o comandos usaste en el punto 33?
$git reflog			*busco commit que pone "Añado titulo..."
$git reset b7182e0
