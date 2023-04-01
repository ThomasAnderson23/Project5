![](https://imgtr.ee/images/2023/03/31/UZKTQ.gif)

# **Cafetería Reveco** 😎



## 1. Introducción 

Aplicación de Comercio electronico construido mediante una API encargada de la gestión de rutas, manejo de datos y seguridad Autenticación (registro e inicio de sesión del usuario mediante JWT) y Autorización(zona privada donde el usurio puede revisar su perfil) utilzando tecnologías de Node con ExpressJS y para Base de datos MongoDB.

## 2. Comenzamos 🏃

**Instalación del proyecto**
- Mover a su directorio de proyecto.
- Clonar el repositorio
- Mover al directorio de proyecto
- Instalar las dependencias

**Endpoints**

Funciones de usuario
- POST **/api/user** - Registrar de usuario
- GET  **/api/user** - Visualizar perfil  de su usuario
- POST **/api/user/signin** - Iniciar sesión
- GET /**api/products** - Visualizar todos los productos

Funciones de administrador
- POST **/api/products **- Creación de usuario
- PUT **api/user/:id** - Edición de usuarios
- DELETE **api/user/:id **- Eliminar usuarios
- POST **api/product** - Crear producto
- DELETE **api/user/:id **- Eliminar producto
- PUT **api/product/:id** - Edición de productos

## 3. Tecnologias utilizadas 🔙 🔚
Este proyecto fue construido con las siguientes tecnologias:
- **Nodejs** - JavaScript Runtime
- **Express** - Framework for Nodejs
- **Mongoose** - NoSQL Database
