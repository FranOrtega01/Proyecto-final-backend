# Proyecto Final Backend - Backend de un Ecommerce

Proyecto Final del curso de Backend de Coderhouse. [Documentación con SwaggerUI](https://proyecto-final-backend-production-8668.up.railway.app/api/documentation/)

## Features
- Log In y Sign Up por JWT utilizando Passport y Bcrypt con Local, Github o Google.
- Cambio de contraseña mediante email via [NodeMailer](#dependencias).
- Estructura de capas de usuarios por roles (User, Premium, Admin).
- Subida de Imagen de Perfil, Documentos e Imágenes de Productos via [Multer](#dependencias)

## Comenzá
- [Ingresá](https://proyecto-final-backend-production-8668.up.railway.app/) para crear una cuenta o ingresar por Github o Google para acceder al Home y Tu Perfil, por defecto tu rol es Usuario.

 ### Usuario: 

  - Al ingresar podrás acceder al Home de productos y Tu Perfil para actualizar tus datos.
  - Leer detalle de productos y agregarlo al Carrito.
  - Terminar la compra y generar un Ticket.
  - Subir los documentos necesarios para convertirse en Premium.

### Premium: 
 
- Crear productos.
- Actualizar o borrar productos creados.

### Admin:
 - Ver, modificar y borrar todos los Usuarios, Carritos y Productos.
 - Modificar los roles de los usuarios.
 - Borrar todos los usuarios con más de dos días de inactividad. 



#


### Dependencias utilizadas {#dependencias}
- [Bcrypt]()
- [Express]()
- [Handlebars]()
- [JWT]()
- [Multer]()
- [Passport]()
- [UUID]()
- [Winston]()
- [Socket.io]()
- [@faker-js]()
- [Mongoose]()
- [Swagger]()
- [NodeMailer]()

### Tecnologias utilizadas
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)  
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens) ![Mocha](https://img.shields.io/badge/-mocha-%238D6748?style=for-the-badge&logo=mocha&logoColor=white) ![Chai](https://img.shields.io/badge/chai.js-323330?style=for-the-badge&logo=chai&logoColor=red)


### Author
[Franco Ortega](https://www.linkedin.com/in/franco-ortega-48838123b/)