# PracticaGit - Respuestas

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1` 

Se borra el último commit de forma brusca, sin guardar los cambios del working copy.

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reset --hard c575b24` 

Mediante git reflog, copio el código del commit al que quiero volver y con git reset --hard vuelvo a él.

--

**3. El merge del paso 13,¿Causó algún conflicto?
¿Porqué?**

No se producen conflictos, la consola responde al merge: already up to date.

--

**4. El merge del paso 19,¿Causó algún conflicto?¿Porqué?**

Se produce un conflicto debido a la modificación del mismo archivo .md en las dos ramas.

Automatic merge failed; fix conflicts and them commit the result.

--

**5. El merge del paso 21,¿Causó algún conflicto?¿Porqué?**

No, la rama master absorve a styled sin problemas mediante git merge styled.

--

**6. ¿Qué comando o comandos utilizaste en el paso 25? ¿Por qué?**

`git graph` 

Para ver el dibujo gráfico / diagrama de los commits que he ido haciendo.

--

**7. El merge del paso 26,¿Podría ser fastforward?¿Porqué?**

Si, se encuentran en la misma linea, no en una bifurcación de las ramas.

--

**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reflog` y `git checkout 9d5183e` 

--

**9. ¿Qué comando o comandos utilizaste en el paso 28?**


--

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -D title`

--

**11. ¿Qué comando o comandos utilizaste en el paso 30?**

`git reflog` , `git checkout +codigo`

--

**12. ¿Qué comando o comandos utilizaste en el paso 32?**

`git reflog` , `git checkout 167275a`

--

**13. ¿Qué comando o comandos utilizaste en el paso 33?**

`git reflog` , `git checkout 9d5183e`

--

