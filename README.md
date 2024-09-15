# Practica_GitHub
Solución de la práctica

Ejercicio 1:

- ¿Qué comando utilizaste en el paso 11? ¿Por qué? 
Apliqué el commando git reset –hard Head~1 porque desahace el último commit y lo que habia en el Workingcopy- El staging area queda vacio.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Apliqué los commandos:
Git reflog
git reset –hard afbc000
porque el git reflog me permite obtener el ID del cambio que debo restaurar.

- El merge del paso 13, ¿Causó algún conﬂicto? ¿Por qué? 
No se generó ningun conflicto porque la branch main no tiene ningún cambio que no este en styled

- El merge del paso 19, ¿Causó algún conﬂicto? ¿Por qué? 
Sí causó un conflicto porque las dos ramas modifican el mismo archivo en las mismas lineas.

- El merge del paso 21, ¿Causó algún conﬂicto? ¿Por qué?
No causó ningun conflicto porque solamente la mrama styled modifica un archivo. La rama main no modificó dicho archivo desde el punto en el que se creó la rama styled

- ¿Qué comando o comandos utilizaste en el paso 25? 
Usé el commando git log  --graph –decorate –pretty

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 
Si, porque hay un solo commit en el branch title

- ¿Qué comando o comandos utilizaste en el paso 27?
Usé el commando Git reset HEAD~1 –soft

- ¿Qué comando o comandos utilizaste en el paso 28?
Por error, deshice el merge en lugar de desechar los cambios. 

- ¿Qué comando o comandos utilizaste en el paso 29?
Git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?
Git reflog
Git reset 5760ed0

- ¿Qué comando o comandos usaste en el paso 32?
Git log
Git checkout 9ad845421c3e4d47400450f4d65a5688b19ef8f0 (commit donde se creo el archive inicial)

- ¿Qué comando o comandos usaste en el punto 33?
Git reflog
Git checkout 5760ed0
