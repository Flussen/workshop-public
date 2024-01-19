# workshop-public

Hola!

Este taller tiene que ser presentado como una aplicacion de springboot que va a contar como una API RestFUL

## Requisitos
La API debe cumplir con los siguientes requisitos:

1. La aplicación debe de constar con un modelo de usuario el cual constará de los siguientes datos
```
User {
    id String
    username String
    password String
    email String
    registeredAt Date
}
```
* La **id** debe ser un UUID
* La **contraseña** debe de ser encriptada con bcrypt
* **registeredAt** debe de ser un de tipo fecha

---

2. La API debe de tener endpoints para las siguientes interacciones

* Obtener usuario por ID
* Obtener usuarios por el usuario
* Crear usuarios, para crear un usuario es necesario pasarle un usuario, contraseña y email, el registeredAt debe de ser generado automaticamente al crear el usuario
* Modificar la contraseña por una nueva, la contraseña nueva tambien debe de ser encriptada

---

* Todo debe estar conectado a una base de datos
* Dejar el archivo SQL de la tabla usuarios en resources


### Para tener en cuenta
* Tener buenas practicas
* Evita el codigo comentado


> Workshop by [@GalassoX](https://github.com/GalassoX)