# Servidor de Usuarios con Node.js y PostgreSQL

## 🚀 Instrucciones para ejecución

1. Clonar el repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd servidor-usuarios


Instalar dependencias:

npm install


Configurar conexión en db.js:

Actualizar usuario y contraseña de PostgreSQL.

Crear base de datos y tabla:

CREATE DATABASE usuarios_db;
CREATE TABLE usuarios (
  id SERIAL PRIMARY KEY,
  nombre VARCHAR(50),
  correo VARCHAR(100),
  contraseña VARCHAR(100)
);


Ejecutar el servidor:

node server.js


Probar endpoints:

GET /usuarios

POST /usuarios

PUT /usuarios/:id

DELETE /usuarios/:id

Servidor disponible en:
👉 http://localhost:3000
