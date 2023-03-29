# godBootcamp
class notes rulea bootcamp

Logica de los TICKETs VALIDATION QUESTIONS 1, 2 ->   __ VERSION _ 1

Cada pagina de preguntas contiene 3 respuestas cuyas respuestas se encuentran envueltas en un tag <p> que contiene un <input> que es chek de la respuesta seleccionada y un <label> con el contenido de la respuesta, cada una con un ID en orden ascendente

Desde JS se seleccionan los 3 pares de <input> y <label> y se almacenan en variables **

Creamos una funcion guardar() que enviara los datos al sessionStorage

Dentro de la funcion escuchamos el evento 'click' y con condicionales validamos cual respuesta / input fue seleccionada/ chekeada **

Al tener la respusta seleccionada buscamos el value del input para saber a que respuesta equivale y emparejamos el contenido del label que tiene la respuesta en texto con el valor del input para luego enviarlos al sessionStorage con un identificador ( dato 1-2-3)


Logica TICKET VALIDATION RESULT

Para validar las respuestas correctas y mostrarlas en result.html

Dentro de la funcion guardar() y luego de validar la respuesta correcta enviamos al sessionStorage el valor de la respuesta que sera la "llave" para luego validarla en result.html y agregarle una clase con el color que corresponda


