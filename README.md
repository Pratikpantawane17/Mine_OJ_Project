# Mine_OJ_Project

Workflow => 
my-online-judge/
├── client/                   # React Frontend
│   ├── public/
│   └── src/
│       ├── components/
│       │   ├── HomePage.jsx
│       │   ├── ProblemPage.jsx
│       │   ├── Leaderboard.jsx
│       │   └── Navbar.jsx
│       ├── App.js
│       └── index.js
├── server/                   # Node.js Backend
│   ├── controllers/
│   │   ├── problemController.js
│   │   ├── submissionController.js
│   │   └── userController.js
│   ├── models/
│   │   ├── Problem.js
│   │   ├── Solution.js
│   │   ├── TestCase.js
│   │   └── User.js
│   ├── routes/
│   │   ├── problemRoutes.js
│   │   ├── submissionRoutes.js
│   │   └── userRoutes.js
│   ├── utils/
│   │   └── codeRunner.js         # Uses child_process and Docker
│   ├── config/
│   │   └── db.js
│   ├── app.js
│   └── server.js
├── .env
├── package.json
├── README.md
└── Dockerfile (optional for backend containerization)
