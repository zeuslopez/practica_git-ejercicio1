# Respuestas al ejercicio 1

<br/>- ¿Qué comando utilizaste en el paso 11? ¿Por qué?<br/>
$git reset --hard HEAD~1

*reset para deshacer el ultimo commit, hard para deshacer incluso lo que hay en el working copy, y HEAD~1 para indicarle volver al commit padre*<br/>

<br/>- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?<br/>
$git reflog			*para ver logs y saber SHA de ultima referencia*<br/>
$git reset --hard 64a0fe3	*para rehacer los cambios en working copy*<br/>

<br/>- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?<br/>
$git merge master		*No causó conflicto porque no hubos cambios en commits*<br/>

<br/>- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?<br/>
$git merge htmlify		*No, al no haber cambios en las versiones del archivo en cada rama*<br/>

<br/>- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?<br/>
$git merge styled. 		*No, al no haber commits que no tenga ya la rama master*<br/>

<br/>- ¿Qué comando o comandos utilizaste en el paso 25?<br/>
$git log --graph		*También se podia haber añadido --pretty para mostrarlo mas resumido*<br/>

<br/>- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?<br/>
$git merge --no-ff title	*No , porque saltaria conflicto al haber cambios en git-nuestro.md al no saber cual es la version buena*<br/>

<br/>- ¿Qué comando o comandos utilizaste en el paso 27?<br/>
$git reset HEAD~1

<br/>- ¿Qué comando o comandos utilizaste en el paso 28?<br/>
$git reflog			*Para saber el SHA al que debo moverme*<br/>
$git reset a091fce

<br/>- ¿Qué comando o comandos utilizaste en el paso 29?<br/>
$git branch -d title

<br/>- ¿Qué comando o comandos utilizaste en el paso 30?<br/>
$git reflog			*Para saber el SHA al que debo moverme*<br/>
&git reset a091fce

<br/>- ¿Qué comando o comandos usaste en el paso 32?<br/>
$git reflog					<br/>
$git reset

<br/>- ¿Qué comando o comandos usaste en el punto 33?<br/>
$git reflog			*busco commit que pone "Añado titulo..."*<br/>
$git reset b7182e0
