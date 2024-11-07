# JWT-Basics

## Descripción
Pequeña API para el entendimiento de funcionalidades básicas de JasonWebToken (JWT). Construida en Node.js pero a diferencia del [users_management](https://github.com/DiegoBottegoni/users_management) subido anteriormente al repositorio, sin base de datos ya que el objeto de esta app fue aprender mejor las funcionalidades básicas de JWT, para restringir accesos a través de tokens y su respectivo manejo de errores, cubriendo cada uno con la ayuda de http-status-codes para practicidad.
JWT-Basics cuenta con un template front-end que no es de mi autoría pero resutla extremadamente útil y productiva para probar la API.

## Tecnologías utilizadas
- **Node.js, express, express-async-errors, http-status-codes, dotenv, jsonwebtoken**

## Instalación

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/DiegoBottegoni/JWT-Basics.git
   
2. Navegar a la carpeta del proyecto:

   ```bash
   cd JWT-Basics

3. Instalar las dependencias:

   ```bash
   npm install
   
4. Crear un archivo .env en la raíz del proyecto y agregar tus variables de entorno. Por ejemplo:

   ```bash
   JWT_SECRET=tu_secreto_jwt

5. Iniciar el servidor:

   ```bash
   npm start
