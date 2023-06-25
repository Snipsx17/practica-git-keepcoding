## Practica del modulo de GIT

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
  utilizo el comando `git reset --hard HEAD~1` para deshacer el ultimo commit y volver el
  working copy al estado anterior.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
  utilizo el comando `git reflog` para buscar el identificador del commit que deshice y con
  `git reset --hard 36135f0` rehago el commit deshecho.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
  No causo ningun conflicto porque es un **merge** fast-forwar.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
  Si causo un conflicto porque en las ramas styled y htmlfy modifique el archivo git-nuestro.md
  en las mismas lineas

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
  No causo ningun conflicto porque fue un **merge** fast-forwar, no existian cambios en las mismas
  lineas de los archivos de las ramas.
- ¿Qué comando o comandos utilizaste en el paso 25?
  `git log --graph --branches --oneline`

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
  Si, porque las 2 ramas estaban en la misma linea

- ¿Qué comando o comandos utilizaste en el paso 27?
  `git reset HEAD~1`

- ¿Qué comando o comandos utilizaste en el paso 28?
  `git restore git-nuestro.md`

- ¿Qué comando o comandos utilizaste en el paso 29?
  `git title -d`

- ¿Qué comando o comandos utilizaste en el paso 30?
  `git reflog`, busque la referencia del commit donde hice el merge y luego use `git reset --hard 1286bd5`
  para recuperar el merge

- ¿Qué comando o comandos usaste en el paso 32?
  `git checkout 2fd2da5`

- ¿Qué comando o comandos usaste en el punto 33?
  `git checkout main`
