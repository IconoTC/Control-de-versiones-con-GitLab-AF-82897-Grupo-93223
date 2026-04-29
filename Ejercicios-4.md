# Ejercicios - Tema 4: Tags, Releases, Workflows y Automatización en Git

A continuación, encontrarás 10 ejercicios prácticos sobre tags, releases, distintos workflows de trabajo en Git, hotfixes, `.gitignore` y hooks. Intenta resolverlos antes de consultar la teoría.

---

## Ejercicio 1. Tags

Investiga qué es un tag en Git y explica con tus palabras para qué sirve. Después, crea un repositorio de prueba, realiza al menos un commit y añade un tag a ese punto del historial. Finalmente, ejecuta el comando necesario para mostrar todos los tags del repositorio.

---

## Ejercicio 2. Releases

Crea una release usando algunos de los tags anteriores.

---

## Ejercicio 3. `.gitignore`

Crea un repositorio de prueba con varios archivos y carpetas, incluyendo algunos que no deberían subirse al repositorio, como archivos temporales, carpetas de dependencias o archivos de configuración local. Después, crea un archivo `.gitignore` y añade reglas para evitar que Git controle esos elementos. Finalmente, comprueba que Git deja de mostrarlos como cambios pendientes.

---

## Ejercicio 4. Hotfixes

Explica qué es un hotfix en Git y en qué situación se utiliza. Después, imagina que una aplicación ya publicada tiene un error urgente en producción. Describe qué pasos seguirías para crear una rama de hotfix, corregir el problema, integrar el arreglo en la rama principal y dejar el repositorio preparado para seguir trabajando con normalidad.

---

## Ejercicio 5. `git revert <commit-hash>`

Realiza varios commits en un repositorio de prueba. Después, elige uno de ellos y reviértelo con el comando `git revert <commit-hash>`. Finalmente, consulta el historial del repositorio.

---

## Ejercicio 6. GitLab Revert

Investiga qué opción ofrece GitLab para revertir cambios desde su interfaz web. Después, explica en qué situación podría resultar útil hacer un revert desde GitLab en lugar de hacerlo manualmente desde la terminal. Finalmente, responde qué precaución deberías tener antes de revertir cambios en un repositorio compartido.

---

## Ejercicio 7. Trunk Based Development

Investiga en qué consiste el workflow `trunk based`. Después, explica cómo se organiza el trabajo en este modelo, qué papel tiene la rama principal y qué ventajas puede tener en equipos que integran cambios con mucha frecuencia. Finalmente, practica creando un repositorio donde uses esta estrategia para actualizar los cambios.

---

## Ejercicio 8. Forking Workflow y Feature Branch Workflow

Explica con tus palabras en qué consiste el `forking workflow` y en qué consiste el `feature branch workflow`. Después, compáralos brevemente indicando en qué se diferencian y en qué tipo de proyecto o equipo podría ser más recomendable cada uno de ellos.

---

## Ejercicio 9. Gitflow Workflow

Investiga cómo funciona el workflow `gitflow`. Después, identifica qué papel suelen tener ramas como `master`, `develop`, `feature`, `release` y `hotfix`. Responde qué ventajas puede ofrecer este modelo en proyectos grandes y qué posible inconveniente puede tener frente a workflows más simples.

Por último, crea un repositorio con toda la estructura de ramas necesaria para usar esta estrategia, haciendo varios commits y merges.

---

## Ejercicio 10. GitLab Pipelines

Investiga qué es una pipeline en GitLab y para qué sirve dentro de un proyecto. Después, imagina un repositorio en el que cada vez que se sube código se ejecutan automáticamente tests y comprobaciones. Explica qué ventajas tiene este sistema en un equipo y por qué puede ayudar a detectar errores antes de integrar cambios en la rama principal.

---

## Reto final opcional

Imagina que formas parte de un equipo que va a publicar una nueva versión de un proyecto. Describe un flujo de trabajo completo en el que intervengan un archivo `.gitignore`, ramas de trabajo, un posible hotfix, un tag final, una release y al menos uno de los workflows estudiados. Intenta explicar en qué orden realizarías cada paso y por qué.
