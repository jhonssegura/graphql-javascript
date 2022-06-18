# graphql-javascript

## Ejecutar

    $ node index.js

## Comandos útiles

Hacer una consulta para traer todos los datos con los campos indicados

{
  clientes {
    id
    nombre
    telefono
  }
}


Hace una consulta para traer los datos indicados según el ID

{
  cliente( id: 2 ) {
    id
    nombre
  }
}


Insertar datos

mutation {
  addCliente( nombre:"Jhon", telefono:"916 434 434" ) {
    id
    nombre
    telefono
  }
}