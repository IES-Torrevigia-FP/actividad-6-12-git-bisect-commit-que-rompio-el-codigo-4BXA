##Explica con tus palabras cómo funciona git bisect y qué problema resuelve.
Es una herramienta de Git que sirve para encontrar rápidamente qué cambio (commit) introdujo un error en tu proyecto.


##Describe una situación real en un proyecto donde git bisect sería especialmente útil (por ejemplo, bugs que aparecen después de muchos commits).
Cuando un bug no es evidente a simple vista, hay muchos commits entre "funciona" y "no funciona".


##¿Qué requisitos previos debe cumplir el proyecto para que git bisect sea eficaz (tests reproducibles, saber qué es “buggy” y qué no, etc.)?
El proyecto debe permitir identificar claramente cuándo una versión es “buena” o “mala”, contar con un bug reproducible, poder ejecutarse correctamente en cada commit, y mantener un entorno consistente.
