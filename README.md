<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6B6B,50:FD297B,100:FF6348&height=180&section=header&text=DevTinder&fontSize=45&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Where%20Developers%20Connect&descSize=18&descAlignY=55&descColor=ffffff" width="100%" />

</div>

## 💻 About

**DevTinder** is a developer matching platform inspired by Tinder's swipe-based UX. Discover other developers, swipe right to connect, build your network, and collaborate on projects. Built as a full-stack application with React frontend and Node.js/Express backend.

## ✨ Features

- 👤 **User Profiles** — Create and customize your developer profile with skills, bio & experience
- 👆 **Swipe to Connect** — Tinder-style card swiping to discover and connect with developers
- 💬 **Match System** — Get notified when another developer swipes right on you
- 🔐 **Authentication** — Secure login/signup with JWT-based session management
- 📋 **Feed** — Personalized developer feed based on your preferences
- 🔗 **Connection Requests** — Send, accept, or reject connection requests
- 📱 **Responsive UI** — Works seamlessly across desktop and mobile devices

## 🛠️ Tech Stack

<div align="center">

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Redux](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![DaisyUI](https://img.shields.io/badge/DaisyUI-5A0EF8?style=for-the-badge&logo=daisyui&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

</div>

## 🏗️ Architecture

```
devTinder/
├── devTinder-web/          # Frontend (this repo)
│   ├── src/
│   │   ├── components/     # React components
│   │   │   ├── Login.jsx       # Auth page
│   │   │   ├── Feed.jsx        # Dev card feed
│   │   │   ├── Profile.jsx     # User profile
│   │   │   ├── Connections.jsx  # Matched devs
│   │   │   └── Requests.jsx    # Pending requests
│   │   ├── utils/          # API calls, helpers
│   │   └── store/          # Redux state management
│   └── public/
│
└── devTinder-backend/      # Backend API
    ├── src/
    │   ├── routes/         # API endpoints
    │   ├── models/         # MongoDB schemas
    │   ├── middleware/     # Auth & validation
    │   └── config/        # DB & app config
    └── package.json
```

## 🚀 Getting Started

### Prerequisites
- Node.js 16+
- MongoDB (local or Atlas)

### Frontend Setup

```bash
# Clone the repository
git clone https://github.com/abhi07mehta/devTinder-web.git
cd devTinder-web

# Install dependencies
npm install

# Start the development server
npm run dev
```

### Backend Setup

```bash
# Clone the backend repo (if separate)
# Install dependencies & configure MongoDB connection
# Start the server
npm run dev
```

## 🔌 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| `POST` | `/signup` | Register a new user |
| `POST` | `/login` | Authenticate & get JWT |
| `GET` | `/profile/view` | Get current user profile |
| `PATCH` | `/profile/edit` | Update profile info |
| `GET` | `/feed` | Get developer feed |
| `POST` | `/request/send/:status/:userId` | Send interest/pass |
| `POST` | `/request/review/:status/:requestId` | Accept/reject request |
| `GET` | `/user/connections` | Get matched connections |
| `GET` | `/user/requests/received` | Get pending requests |

## 📚 What I Learned

- Building Tinder-style swipe UX with React
- Full-stack MERN application architecture
- JWT-based authentication flow
- MongoDB schema design with Mongoose
- Redux Toolkit for frontend state management
- RESTful API design patterns
- Middleware-based request validation

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

**Built with ❤️ by [Abhishek Mehta](https://github.com/abhi07mehta)**

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6B6B,50:FD297B,100:FF6348&height=100&section=footer" width="100%" />
