Desarrolladores se Equivocaron 
En la línea 44: "let randomNumber = Math.random() * 10;"
faltando el foor y Math y el numero mayor seria 100 la solucion:
let randomNumber = Math.floor(Math.random() * 100) + 1;
///
En la línea 58: "let userGuess = guessField.value;"
se convirtio el input a número: let userGuess = Number(guessField.value);
tambien se equivocaron en los comentario de '¡Felicidades! ¡Adivinaste el número!' andaba el de perdiste , andaba viceversa.
///
En la línea 87,95: "guessSubmit.addeventListener('click', checkGuess);"
"addeventListener" Estaba mal escrito , la forma correcta seria addEventListener
///
En la línea 114: "randomNumber = Math.floor(Math.random()) + 1;"
se corrigio randomNumber = Math.floor(Math.random() * 100) + 1; Faltando el numero mayor 100
///

