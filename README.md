# Taller JWT y APIs REST

Taller de autenticación con JSON Web Tokens (JWT) y creación de APIs REST con Node.js y PHP.

## Estructura del proyecto
- `api-jwt-node/`: Servidor en Node.js con Express y JWT.
- `api-jwt-php/`: Servidor en PHP nativo con Firebase JWT.
- `postman/`: Colección de pruebas para Postman.

## Ejecución

### Node.js
```bash
cd api-jwt-node
npm install
node server.js
```

### PHP
```bash
cd api-jwt-php
composer install
php -S localhost:8000
```

## Pruebas
Importar la colección de Postman ubicada en `postman/taller_jwt.postman_collection.json` para probar las rutas de login y tareas.
