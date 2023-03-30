Erro 1 la funcion checkGuess no se estaba llamando correctamente:
en la line 87 se estaba escribiendo guessSubmit.addeventListener y no estaba siendo reconocida como una funcion y lo correcto seria guessSubmit.addEventListener con E mayuscula

Error 2 en la linea 49
No se estaba llamando correctamente al div, incorrecto: const lowOrHi = document.querySelector('lowOrHi'); correcto: const lowOrHi = document.querySelector('.lowOrHi');. Se debe colocar un punto al principio del nombre.

Numero aleatorio entero linea 44
Para generar un numero aleatorio 1-100 y que sea entero debemos usar el metodo floor: let randomNumber = Math.floor(Math.random()*100); o en su lugar let randomNumber = Math.parseInt(Math.random()*100);

Validacion de numero y entero
Uno de los requerimientos es que el juego funcione solo con numeros enteros para eso se realizan 2 validaciones una que verifica si el valor ingresado es una letra o caracter si es asi se mostrara una alerta de lo contrario no hara nada, la segunda validacion verifica si es un numero entero o decimal, si es decimal se mostrara una alerta indicando que se ingresen solo numeros enteros

Valor requerido
En el input text agregue un required el cual indica que el valor sera requerido para funcionar

Color del mensaje mayor
El color del mensaje es color verde cuando debe de ser negro

Mensaje mayor
Al ingresar un numero mayor el mensaje que muestra es: "Incorrecto! El número es menor!" y el correcto debe ser: "Incorrecto! El número es mayor!"

Mensaje menor
Al ingresar un numero mayor el mensaje que muestra es: "Incorrecto! El número es mayor!" y el correcto debe ser: "Incorrecto! El número es menor!"

Intentos
El juego actualmente solo cuenta con 5 intentos y deben de ser 10 se cambia el valor de la constante ATTEMPS=10

10 intentos
Luego de los 10 intentos si no adivina el numero no aparece el mensaje perdiste y muestra felicitaciones adivinaste el numero

Color del mensaje perdiste
Actualmente muestra en color negro y debe de ser en color rojo

No llama a la funcion para reestablecer el juego
En la linea 108 esta escrito: resetButton.addeventListener('click', resetGame); cuando debe de ser: resetButton.addEventListener('click', resetGame);

Linea 126
Correccion: randomNumber = parseInt(Math.random()*100);

Validacion de numero correcto
En la linea 75 solo se deben usar 2 signos "="