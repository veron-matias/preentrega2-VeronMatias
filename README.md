# preentrega-VeronMatias
El sistema consiste en que un profesor pueda ingresar el o los nombres y apellidos de los alumnos de su materia, el cual le devolvera como resultado si el alumno tiene aprobado o no el final del año mostrando su promedio.
Al final del ingreso de los datos, el usuario podra ver su materia seleccionada, la cantidad de alumnos que ingreso (si no ingreso alumnos mostrara otra informacion), la cantidad de aprobados y desaprobados 
Los datos a ingresar estan validados, de tal manera que no puede avanzar si ingresa solo letras cuando pide numeros y viceversa.

Agregados de la segunda entrega:
- Cambio de la linea del script en html. Llevandolo al final para evitar futuros problemas.
- Se simplificaron lineas de codigo y eliminaron lineas que ya no son utiles. 
- Al momento de mostrar los resultados, se discrimina por aprobados y desaprobados por nombre y apellido (guardados en un array). 
- Se añade un boton en el HTML el cual ejecuta la funcion de buscar el alumno por apellido:
    .Si no lo encuentra, lo informa por un alert.
    .Si es encontrado, se informa por consola en una tabla, mostrando nombre, apellido y promedio final.
    .Si no se ingreso ningun alumno, el boton funcionara pero mostrara una alerta de que no hay alumnos ingresados. # preentrega2-VeronMatias
