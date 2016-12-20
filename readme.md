#Cuestionario

- **¿Qué comando utilizaste en el paso 11? ¿Por qué?**

	`git reset --hard HEAD~1` deshace el commit y lo que había en el working copy.


- **¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
	
	`git reflog` para ver el identificador del commit al que quiero volver y `git checkout 69cee35` para ir a ese commit

- **El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

	No, porque al usar `checkout` se ha modificado el working copy y vuelvo a tener el fichero git-nuestro.md como estaba en la rama master 

- **El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

	No, porque las ramas forman una lista. Se ha movido el puntero de styled a donde se encontraba htmlify. Se ha hecho merge fast forward.

- **El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

	No, la situación es idéntica al paso 19. Se vuelve a hacer merge fast forward.

- **¿Qué comando o comandos utilizaste en el paso 25?**

	`git config alias.graph "log --graph --decorate --pretty=oneline"` para crear el alias y luego `git graph` para mostrar el diagrama con las opciones indicadas.

- **El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

	No, porque las ramas no apuntan al mismo commit.

- **¿Qué comando o comandos utilizaste en el paso 27?**

	`git reset HEAD~1`

- **¿Qué comando o comandos utilizaste en el paso 28?**

	`git checkout -- git-nuestro.md`

- **¿Qué comando o comandos utilizaste en el paso 29?**

	`git branch -D title`

- **¿Qué comando o comandos utilizaste en el paso 30?**

	`git reflog`

	`git checkout 8f33fa8`

	`git branch title`

	`git checkout title`

- **¿Qué comando o comandos usaste en el paso 32?**

	`git checkout f7c3dc5`

	`git branch styled`

	`git checkout styled`

- **¿Qué comando o comandos usaste en el punto 33?**
	
	`git checkout 751da63`

	`git branch htmlify`

	`git checkout htmlify`