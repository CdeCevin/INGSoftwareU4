Estructura del codigo:

  Client
  └── (Frontend)
  ...
  
  Server
  ├── Controllers
  │   └── (Lógica del backend y acciones)
  ├── Routes
  │   └── (Organiza todas las rutas del backend y las conecta con los controladores correspondientes)
  ├── db
  │   └── (Conexión a la base de datos)
  ├── node_modules
  │   └── (Módulos necesarios)
  ├── package-lock.json
  ├── package.json
  └── server.js
      └── ( configura y arranca el servidor Express para manejar una API RESTful)
