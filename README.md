# mern-dashboard
Build a premium, full-stack Task Management Dashboard using the MERN (MongoDB, Express, React, Node.js) stack. The application will feature JWT authentication, a modern Kanban and List view dashboard, advanced filtering/sorting, task statistics with interactive SVG charts, and a high-end dark glassmorphism aesthetic.
c:\Users\hp\New folder\
├── package.json (root runner)
├── backend/
│   ├── config/
│   │   └── db.js
│   ├── middleware/
│   │   └── authMiddleware.js
│   ├── models/
│   │   ├── User.js
│   │   └── Task.js
│   ├── routes/
│   │   ├── userRoutes.js
│   │   └── taskRoutes.js
│   ├── .env
│   ├── package.json
│   └── server.js
└── frontend/
    ├── src/
    │   ├── components/
    │   │   ├── Auth.jsx
    │   │   ├── BoardView.jsx
    │   │   ├── ListView.jsx
    │   │   ├── Navbar.jsx
    │   │   ├── Stats.jsx
    │   │   ├── TaskFormModal.jsx
    │   │   └── UI/
    │   ├── context/
    │   │   ├── AuthContext.jsx
    │   │   └── TaskContext.jsx
    │   ├── styles/
    │   │   └── variables.css
    │   │   └── main.css
    │   ├── App.jsx
    │   └── main.jsx
    ├── index.html
    └── package.json
