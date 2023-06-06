Informe de errores
Error 1: Cálculo incorrecto del número aleatorio
Descripción del Error: En la linea `let randomNumber = Math.random() * 10;del archivo index.html, se esta calcul

Solución Propuesta: Reemplazolet randomNumber = Math.random() * 10;con `let randomNumber = Math.floor(Mathlet randomNumber = Math.floor(Math.random() * 100) + 1;para generar un número aleatorio entre 1 y 100, inclusive.

Error 2: Selector incorrect. lower
Descripción del Error: Esconst lowOrHi = document.querySelector('lowOrHi');del archivo index.html, el selector utilizado para obtener el elemento `..lowOrHies incorrecto. EstolowOrHisea null​​y se produzca un error al intentar modificar su contenido.

Solución Propuesta: Cambiar la línea `const lowOrHi = document.querySelectorconst lowOrHi = document.querySelector('lowOrHi');por const lowOrHi = document.querySelector('.lowOrHi');para seleccionar correctamente el elemento por su clase.

Error
Descripción del Error: En la línea `resetButton.addeventListener('clickresetButton.addeventListener('click', resetGame);del archivo index.html, se ha utilizado el nombre de evento incorrecto, lo que provocará que el botón de reinicio no funcione como se espera.

Solución Propuesta: Cambiar la línea `resetButton.addeventListener('clickresetButton.addeventListener('click', resetGame);por resetButton.addEventListener('click', resetGame);asignar para el evento de clic correctamente al botón de reinicio.
