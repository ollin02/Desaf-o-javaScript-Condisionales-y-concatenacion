# 09 Desafío: hora de practicar
<p>Programar requiere práctica. Hemos creado una lista adicional de actividades (no obligatorias) 
  para que practiques y refuerces aún más tu aprendizaje.</p>

## Desafíos
1. Pregunta al usuario qué día de la semana es. Si la respuesta es "Sábado" o "Domingo", muestra "¡Buen fin de semana!". De lo contrario, muestra "¡Buena semana!".
 ```javascript
      let diaSemana = prompt('¿Qé día de la semana es?');
      if(diaSemana.toUpperCase() === "SABADO" || diaSemana.toUpperCase() === "DOMINGO"){
          alert('¡Buen fin de semana!');
      } else {
          alert('¡Buena semana!');
      }
 ```
- otra forma de resolverlo con operador condicional ternario
```javascript
  let diaSemana = prompt('¿Qé día de la semana es?');
  (diaSemana.toUpperCase() === "SABADO" || diaSemana.toUpperCase() === "DOMINGO") ? alert('¡Buen fin de semana!') : alert('¡Buena semana!');
```
2. Verifica si un número ingresado por el usuario es positivo o negativo. Muestra una alerta informativa.
````javascript
      alert("Programa que identifica si un número es positvo, negativo o cero"); 
      let numeroUsuario = parseFloat(prompt("Ingresa un número"));
      if(numeroUsuario == 0) {
           alert(`El ${numeroUsuario} es cero`);
      } else {
          (numeroUsuario > 0)? alert(`El ${numeroUsuario} es positivo`) : alert(`El ${numeroUsuario} es negativo`);
     }
      
````
3. Crea un sistema de puntuación para un juego. Si la puntuación es mayor o igual a 100, muestra "¡Felicidades, has ganado!". En caso contrario, muestra "Intentalo nuevamente para ganar.".
````javascript
   let puntuación = prompt('Dijita una puntuación');
   (puntuación>=100)? alert("¡Felicidades, has ganado!") : alert("Intentalo nuevamente para ganar.");
````
4. Crea un mensaje que informe al usuario sobre el saldo de su cuenta, utilizando un template string para incluir el valor del saldo.
````javascript
  let saldo = 1500;
  alert(`Tu saldo es ${saldo}`);    
````
5. Pide al usuario que ingrese su nombre mediante un prompt. Luego, muestra una alerta de bienvenida usando ese nombre.
````javascript
let nombreUsuario = prompt('Por favor, ingresa tu nombre');
alert(`Bienbenido, ${nombreUsuario}`);
````   

