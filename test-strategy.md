Se realizo un analisis al codigo y se determino que hacia falta la conversión a entero y se valida que el valor este entre 1 y 100, si la entrada no es valida, se muestra una alerta y se detiene la ejecución sin incrementar el contador de intentos

Se encuentra un error tipografico en la contante const ATTEMPTMS ya que esta escrita de esta manera const ATTEPS por lo que se procede a su correción

La validación de entrada esta presente pero faltaba la logica posterior a la función

Los colores en cada anuncio "perdiste, adivinaste el numero" no estaban en su lugar apropidado por lo que se cambian los mensajes y colores a donde corresponde

Se evualua nuevamente y se determina que existia un conflicto en la comparación del numero ya que lo tomaba como una cadena y no como un entero por lo que se ajusta  la validación del numero entre 1 y 100 se agrega el fragmento "|| !Number.isInteger(userGuess)"

Si dato ingresado no se contara y se define de la siguiente manera "guessField.value = ''; guessField.focus(); return;"

