Citizen-Connect-Bangladesh/
│
├── client/                         # React Frontend
│
│   ├── public/
│   │   ├── favicon.ico
│   │   ├── logo.png
│   │   └── locales/
│   │       ├── en.json
│   │       └── bn.json
│   │
│   ├── src/
│   │
│   │   ├── app/
│   │   │   ├── store.js
│   │   │   └── queryClient.js
│   │
│   │   ├── assets/
│   │   │   ├── images/
│   │   │   ├── icons/
│   │   │   └── animations/
│   │
│   │   ├── routes/
│   │   │   ├── AppRoutes.jsx
│   │   │   ├── ProtectedRoute.jsx
│   │   │   └── RoleRoute.jsx
│   │
│   │   ├── layouts/
│   │   │   ├── PublicLayout.jsx
│   │   │   ├── CitizenLayout.jsx
│   │   │   ├── AdminLayout.jsx
│   │   │   └── PoliceLayout.jsx
│   │
│   │   ├── pages/
│   │   │
│   │   │   ├── public/
│   │   │   │   ├── Home.jsx
│   │   │   │   ├── About.jsx
│   │   │   │   ├── Contact.jsx
│   │   │   │   └── Transparency.jsx
│   │   │
│   │   │   ├── auth/
│   │   │   │   ├── Login.jsx
│   │   │   │   ├── Register.jsx
│   │   │   │   └── ForgotPassword.jsx
│   │   │
│   │   │   ├── citizen/
│   │   │   │   ├── Dashboard.jsx
│   │   │   │   ├── SubmitReport.jsx
│   │   │   │   ├── MyReports.jsx
│   │   │   │   ├── Notifications.jsx
│   │   │   │   └── Profile.jsx
│   │   │
│   │   │   ├── government/
│   │   │   │   ├── Dashboard.jsx
│   │   │   │   ├── Reports.jsx
│   │   │   │   ├── Analytics.jsx
│   │   │   │   ├── GISMap.jsx
│   │   │   │   └── Departments.jsx
│   │   │
│   │   │   └── police/
│   │   │       ├── LostPersons.jsx
│   │   │       └── EmergencyAlerts.jsx
│   │
│   │   ├── features/
│   │   │
│   │   │   ├── auth/
│   │   │   ├── reports/
│   │   │   ├── roadDamage/
│   │   │   ├── lostPersons/
│   │   │   ├── emergency/
│   │   │   ├── notifications/
│   │   │   ├── chatbot/
│   │   │   ├── analytics/
│   │   │   └── users/
│   │
│   │   ├── components/
│   │   │
│   │   │   ├── common/
│   │   │   ├── maps/
│   │   │   ├── charts/
│   │   │   ├── forms/
│   │   │   ├── navbar/
│   │   │   ├── sidebar/
│   │   │   └── modals/
│   │
│   │   ├── hooks/
│   │   ├── services/
│   │   ├── utils/
│   │   ├── constants/
│   │   ├── contexts/
│   │   ├── i18n/
│   │   └── styles/
│   │
│   ├── package.json
│   └── vite.config.js
│
│
├── server/                         # Express Backend
│
│   ├── src/
│   │
│   │   ├── config/
│   │   │   ├── db.js
│   │   │   ├── cloudinary.js
│   │   │   ├── socket.js
│   │   │   └── gemini.js
│   │
│   │   ├── api/
│   │   │
│   │   │   ├── auth/
│   │   │   ├── users/
│   │   │   ├── reports/
│   │   │   ├── roadDamage/
│   │   │   ├── lostPersons/
│   │   │   ├── emergency/
│   │   │   ├── notifications/
│   │   │   ├── analytics/
│   │   │   ├── chatbot/
│   │   │   └── departments/
│   │
│   │   ├── controllers/
│   │   ├── services/
│   │   ├── repositories/
│   │   ├── middlewares/
│   │   ├── validators/
│   │   ├── routes/
│   │   ├── models/
│   │   ├── sockets/
│   │   ├── jobs/
│   │   ├── utils/
│   │   └── constants/
│   │
│   ├── uploads/
│   ├── package.json
│   └── server.js
│
│
├── ai-services/
│
│   ├── road-damage-ai/
│   │   ├── classifier.py
│   │   ├── severity.py
│   │   └── model/
│   │
│   ├── face-recognition/
│   │   ├── matcher.py
│   │   ├── encoder.py
│   │   └── dataset/
│   │
│   ├── duplicate-detection/
│   │   └── duplicate.py
│   │
│   └── recommendation-engine/
│       └── recommendation.py
│
│
├── docs/
│   ├── ERD.png
│   ├── Architecture.png
│   ├── API_Documentation.md
│   └── README.md
│
│
├── docker/
│   ├── Dockerfile.client
│   ├── Dockerfile.server
│   └── docker-compose.yml
│
│
├── .github/
│   └── workflows/
│       └── deploy.yml
│
│
├── .env.example
├── README.md
└── package.json
