# Instrucciones básicas de Git

## Comandos principales
- git init — inicializa un repositorio nuevo.
  Ejemplo:
    git init

- git status — muestra los cambios pendientes.
  Ejemplo:
    git status

- git add — añade ficheros al área de preparación (staging).
  Ejemplo:
    git add fichero.txt

- git commit — crea un commit con los cambios añadidos.
  Ejemplo:
    git commit -m "Mensaje del commit"

- git branch — lista/crea ramas.
  Ejemplo:
    git branch nombre-rama

- git checkout — cambia de rama.
  Ejemplo:
    git checkout nombre-rama

- git checkout -b — crea y cambia a una rama nueva.
  Ejemplo:
    git checkout -b nueva-rama

- git merge — fusiona otra rama en la actual.
  Ejemplo:
    git merge otra-rama

- git push — sube commits a remoto.
  Ejemplo:
    git push origin main

- git pull — trae y fusiona cambios desde remoto.
  Ejemplo:
    git pull origin main