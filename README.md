<div align="center">

  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/JSON%20Server-000000?style=for-the-badge&logo=json&logoColor=white" />

  <h1>Task Manager SPA</h1>
  <p>Aplicación de página única para gestión de tareas construida con JavaScript vanilla y Vite. Incluye autenticación con roles (Admin/User), guardián de rutas, dashboard y CRUD completo de tareas.</p>

</div>

---

## Vistas

| Vista | Descripción |
|---|---|
| `Login / Register` | Autenticación y registro de usuarios |
| `Dashboard` | Resumen de tareas del usuario |
| `Task` | Listado de tareas con filtros |
| `CreateTask` | Formulario de creación de tareas |
| `Profile` | Perfil del usuario |

## Arquitectura
```
PruebaJavaScript/
├── index.html             
├── styles.css                
├── package.json
├── package-lock.json
├── README.md
├── .gitignore
└── src/
      ├── main.js             
      ├── components/            
      │   ├── Menu.js
      │   └── NavBar.js
      ├── views/                
      │   ├── CreateTask.js
      │   ├── Dashboard.js
      │   ├── Profile.js
      │   └── Task.js
      ├── router/                 
      │   └── Router.js
      ├── state/               
      │   ├── db.json
      │   └── sessionManager.js
      ├── services/             
      │   ├── api.js
      │   ├── taskService.js
      │   └── authService.js
      ├── auth/ 
      │   ├── Login.js
      │   └── Register.js
      └── utils/             
          ├── helpers.js
          └── validators.js      
````

## Tecnologías

- JavaScript vanilla con ES6 Modules
- Vite como bundler
- JSON Server como API REST simulada
- CSS personalizado con animaciones

## Instalación y uso

```bash
git clone https://github.com/maryhug/task-manager-spa.git
cd task-manager-spa
npm install
```

```bash
# Terminal 1 — API REST
npm run server

# Terminal 2 — Frontend
npm run dev
```

## Test Users
- Admin
  - Email: admin@admin.com
  - Password: admin123
- User
  - Email: user@test.com
  - Password: user123

## Frontend
- https://www.figma.com/design/K3PmKIOlfEsjnbwP54Yc2x/Sin-t%C3%ADtulo?node-id=33-2&p=f
