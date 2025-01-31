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
      alert("Programa que identifica si un número es positvo o negativo"); 
      let numeroUsuario = parseFloat(prompt("Ingresa un número"));
      (numeroUsuario > 0)? alert(`El ${numeroUsuario} es positivo`) : alert(`El ${numeroUsuario} es negativo`);
   ````
