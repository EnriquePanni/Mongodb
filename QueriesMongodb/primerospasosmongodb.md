# Primeros comandos en mongodb

## Mostrar las bases de datos
`showdbs;`
`show databases;`

### Crear una base de datos
*En mongodb para crear una base de datos debe contener por lo menos una coleccion*

`use nombredelabasededatos`
*Ejemplo:*

`use db3;`

### Crear una coleccion

`db.createCollection("Nimbredelacoleccion")`

*Ejemplo:*

`db.createCollection("Alumnos")`

### Mostrar las colecciones de la base de datos

*Ejemplos:*

`show collections;`