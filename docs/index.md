# Código

Para agregar código en línea en Mardown habrá que usar comillas invertidas alrededor del texto que queremos en formato de código.

Cambio de directorio con el comando `cd`.

En caso de que el texto del código ya incluya comillas invertidas, se debe usar comillas invertidas dobles para escapar las comillas internas, el código quedaría así:

``let str = `texto de la cadena`;``

## Bloques de código

Si el código que queremos agregar consta de más de una línea, debemos agregar un bloqur de código. Para ellos tenemos que usar al menos cuatro espacios o una tabulación al inicio de la línea:

    1et num = 5;
    num++;

## Lista de tareas

Las listas de tareas se componen de checkboxes que se mostrarán al lado del contenido. Para crear una tarea en una lista de tareas tendrás que agregar un guión - seguido de un espacio en blanco y dos corchetes, siendo uno de apertura y otro de cierre. En el interior de los corchetes podrás agregar:

- Espacio en blanco: Agrega un espacio en blanco para indicar que la tarea no ha sido completada.
- Equis x: Agrega una x para indicar que la tarea ha sido completada.

- [x] Primera tarea
- [ ] Segunda tarea
- [ ] Tercera tarea
