# Prueba de tester 1
Esta prueba evalúa conocimientos de programación en base a una situación que puede pasar dentro de un proyecto de software.
## Software necesarios
* [GIT](https://git-scm.com/downloads)
* Cualquier navegador WEB
## Instrucciones antes de empezar
1.  Crear una cuenta en [Github](https://git-scm.com/book/es/v2/GitHub-Creaci%C3%B3n-y-configuraci%C3%B3n-de-la-cuenta).
2.  Crear un [fork](https://docs.github.com/es/get-started/quickstart/fork-a-repo) a este repositorio.
3.  Clonar el repositorio forkeado en tu computadora.
4.  Úbicate en el repositorio raíz del proyecto (Ubicación del proyecto forkeado en tu computadora).
5.  Abrir desde del navegador el archivo index.html de este proyecto.
## Casos de usos
Un banco financiero implementó el juego, Adivina tu número, la cual consiste en adivinar un número entre 1 al 100 durante 10 intentos. Así mismo para facilitar dicho juego se debe cumplir los siguientes requisitos:
* El número a adivinar debe pertenecer al conjunto de los enteros (e.g. 1, 2, 3...)
* El número que ingresará el jugador debe pertenecer al conjunto de los enteros (e.g. 1, 2, 3...), en caso que no ingrese un número entero, debe mostrarse una alerta al usuario y no se debe incrementar un intento de prueba.
* Sí el número que ingresó el jugador es mayor al número a adivinar, se debe mostrar el siguiente mensaje en color negro: "Incorrecto! El número es mayor!", en caso que sea menor, se debe mostrar: "Incorrecto! El número es menor!".
* Si después de 10 intentos, el usuario no adivina el número, se debe mostrarse el mensaje de color rojo: "!!!Pérdistes!!!"
* Si el usuario adivina el número antes de los 10 intentos, se debe mostrar el mensaje de color verde: "Felicitaciones! adivinaste el número!".
## Situación del proyecto.
El desarrollador implementó toda la interfaz gráfica, y así mismo la lógica del juego en el archivo index.html (Con HTML, Javascript y CSS), sin embargo el equipo de desarrollo cometió el error de no testear dicho proyecto, y lo colocaron en los servidores de producción. Para su sorpresa, al momento de que el cliente lo vió... ¡NO FUNCIONABA NADA!
Dado a esta experiencia, el banco financiero contrató a un tester para realizar las pruebas respectivas con la finalidad de que el proyecto funcione correctamente de acuerdo a los requerimientos dados.
## Plan de ataque
Como tester debes solucionar este problema en tu repositorio de github, así mismo debe presentarle al equipo de desarrollo todos los errores que fuiste encontrando y corregiendo (i.e. Una breve descripción del error y su solución respectiva). Dentro del archivo test-strategy.md, igualmente el lider del equipo recomendó a cada tester, ver la consola del navegador de web para identificar más rápido los errores del proyecto.
## Entregables
Como entregables debe presentar lo siguiente:
* El archivo index.html corregido de acuerdo a las observaciones de testeo, cabe mencionar que este archivo debe ser funcional (Al momento de abrir el proyecto, debe funcionar de acuerdo a la lógica de negocio planteado en este ejercicio).
* El plan de ataque test-strategy.md
## Recursos:
* Event Target: https://developer.mozilla.org/es/docs/Web/API/EventTarget
