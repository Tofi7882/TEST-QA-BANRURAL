1. Error 1 Encontrado: const ATTEMPS = 5; En lógica de negocio planteado en este ejercicio solicitaban que fueran 10 y dentro del codigo esta programado solo 5 intentos 
1. Solucion: Cambiar el valor de la constante para que permita los 10 intentos.

2. Error 2 y 3 Encontrados: guessSubmit.addeventListener('click', checkGuess); resetButton.addeventListener('click', resetGame); metodos mal escrito.
2. Solucion: Escribir bien los metodos.

3. Error 4 Encontrado: const lowOrHi = document.querySelector('lowOrHi');  la referencia no estaba bien definida
3. Solucion: Escribir un .lowOrHi para que se haga la referencia correctamente.

4.Error 5: 

    if(userGuess < randomNumber) {
        lowOrHi.textContent = 'El número es mayor!';
      } else if(userGuess > randomNumber) {
        lowOrHi.textContent = 'El número es menor!';
      }
    }

    Al ejecutar la sentencia if el resultado esperado es el contrario
4. Soluciones: Cambiar la condiciones o cambiar el texto

5. Errores 5,6 y 7: if(guessCount === 1), if(userGuess === randomNumber), else if(guessCount === ATTEMPS) dentro de las sentencias esta escrito un igual extra
5. Soluciones: Quitar el igual demas.

6. Errores 8: 
    if(userGuess == randomNumber) {
      lastResult.textContent = '!!!Pérdistes!!!';
      lastResult.style.backgroundColor = 'black';
      lowOrHi.textContent = '';
      setGameOver();
    } else if(guessCount === ATTEMPS) {
      lastResult.textContent = 'Felicitaciones! adivinaste el número!';
      lastResult.style.backgroundColor = 'red';
      setGameOver();
    }

    Al evaluar si el usuario gano le muestra el mensaje de !!!Pérdistes!!! y si el jugador perdio muestra que gano
6. Solucion: colocar resultado deseado como se debe dentro de la sentencia.

7. Errores 9: De acuerdo a la logica del negocio al momento de mostrar se debe mostrarse el mensaje de color rojo: "!!!Pérdistes!!!",
              se debe mostrar el mensaje de color verde: "Felicitaciones! adivinaste el número!", se debe mostrar el siguiente mensaje en color negro: "Incorrecto! El número es mayor!", en caso que sea menor, se debe mostrar: "Incorrecto! El número es menor!".
7. Soluciones: Se debe de cambiar los colores de cada mensajes acorde a lo solicitado.

8. Error 10: let randomNumber = Math.random() * 10; al obtener el numero random el número a adivinar puede que pertenezca y puede que no pertenezca al conjunto de los enteros (e.g. 1, 2, 3...)
8. Solucion: colocar a la funcion random un rango del 1 al 100 y que solo sean numeros enteros

9. Error 11: El Juego no cumplia con darle una alerta al usuario al ingresar un numero entero y lo tomaba como un intento
9. Solucion: se procedio a crear una condicion donde se evaluara que se habia ingresado numero entero y sino alertar al usuario
             que no habia ingresado un numero entero luego se coloco una bandera para que no aumentara el intento del usuario.
