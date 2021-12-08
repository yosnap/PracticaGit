## Práctica Github

**¿Qué comando utilizaste en el paso 11? ¿Por qué?**
git reset --hard HEAD~1 
Porque con --hard vuelvo al estado anterior deshaciendo los cambios realizados

**¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
git reset --hard <hash del commit 10> (buscándolo con reflow)
Porque quiero recuperar los cambios que he realizado

**El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**
No, ya que no hay ningún cambio en los archivos de los commits

**El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**
Si, porque los archivos en las ramas “htmlfy” y “styled” son distintos en la misma línea

**El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**
No, en la rama master no se ha realizado ninguna modificación

**¿Qué comando o comandos utilizaste en el paso 25?**
git graph (lo he personalizado)

**El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**
Si, porque title es el siguiente commit después de master en fila

**¿Qué comando o comandos utilizaste en el paso 27?**
git reset HEAD~1

**¿Qué comando o comandos utilizaste en el paso 28?**
git checkout git-nuestro.md

**¿Qué comando o comandos utilizaste en el paso 29?**
git branch -D title

**¿Qué comando o comandos utilizaste en el paso 30?**
git reflog
git reset --hard <Hash del commit>

**¿Qué comando o comandos usaste en el paso 32?**
git reflog
git reset --hard <Hash del commit>

**¿Qué comando o comandos usaste en el punto 33?**
git reflog
git reset --hard <Hash del commit>
