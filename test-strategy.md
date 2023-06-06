Las modificaciones que realicé al código original incluyen:

Corregir el cálculo del número aleatorio en la línea let randomNumber = Math.random() * 10;. Reemplacé Math.random() * 10por Math.floor(Math.random() * 100) + 1para obtener un número aleatorio entre 1 y 100, ambos inclusive.

Cambiar el tipo de entrada del campo de adivinanza en el formulario de texto a número. Esto se logra agregando el atributo type="number"al elemento inputcorrespondiente.

Agregar la validación de que el número ingresado por el usuario sea un número entero válido utilizando parseInt()y Number.isNaN(). Si el número ingresado no es válido, se muestra una alerta al usuario y no se incrementa el contador de intentos.

Corregir el selector para el elemento .lowOrHien la línea const lowOrHi = document.querySelector('lowOrHi');. Agregué el punto antes de lowOrHipara seleccionar la clase correctamente, quedando como const lowOrHi = document.querySelector('.lowOrHi');.

Agregar el mensaje correcto cuando el usuario no adivine el número dentro de los 10 intentos en la línea lastResult.textContent = 'Felicitaciones! adivinaste el número!';. Reemplacé el mensaje por '¡Perdiste! El número era: ' + randomNumber.

Corregir el nombre de los eventos para guessSubmity resetButton. Cambié addeventListenerpor addEventListeneren ambas líneas.
