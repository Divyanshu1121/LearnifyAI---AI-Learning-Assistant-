# 🧠 AI Learning Assistant

**AI Learning Assistant** is a powerful educational platform that leverages Artificial Intelligence to revolutionize how students study. By uploading PDF documents, users can instantly interact with their study materials through AI-powered chat, automated summaries, flashcard generation, and quizzes.

The platform operates on a **Freemium model**, offering essential features for free while reserving advanced capabilities and unlimited access for Pro users.

---

## � Repositories

- **Frontend**:(https://github.com/Divyanshu1121/AI-Learning-Assistant---Frontend.git)
- **Backend**: https://github.com/Divyanshu1121/AI-Learning-Assistant---Backend.git

---

## �🚀 Features

### 📚 Document Management
- **PDF Upload**: Upload and organize study materials.
- **Auto-Thumbnails**: Visual representation of documents.
- **Smart Search**: Quickly find documents by title.

### 🤖 AI Study Tools
- **Chat with Document (RAG)**: Ask questions and get answers based *strictly* on your document content. The AI acts as a "Teacher", elaborating on concepts while citing the source.
- **AI Summaries**: Generate structured, bullet-point summaries of entire documents in seconds.
- **Flashcard Generator**: Create study flashcards automatically from your PDFs.
- **Quiz Generator**: Test your knowledge with AI-generated quizzes based on your material.

### 💎 Freemium Subscription System
- **Free Plan**:
    - Manage up to 3 documents.
    - Generate 5 AI Summaries.
    - Create 3 Flashcard sets / Quizzes.
    - Basic access.
- **Pro Plan (Upgrade)**:
    - **Unlimited** Documents, Summaries, Flashcards, and Quizzes.
    - **Priority Support**: Faster processing.
    - **Unlock Features**: Unrestricted access to AI Chat and advanced study modes.

### 🔐 Security & Auth
- **User Authentication**: Secure Login/Register (JWT-based).
- **Password Management**: Forgot/Reset password functionality.
- **Profile Management**: Update user details and plan status.

---

## 🛠️ Tech Stack

### Frontend
- **Framework**: React.js (Vite)
- **Styling**: Tailwind CSS
- **State Management**: Context API (Auth, Theme)
- **Routing**: React Router v6
- **HTTP Client**: Axios
- **Markdown Rendering**: React Markdown + Remark GFM
- **Icons**: Lucide React
- **Notifications**: React Toastify / Hot Toast

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB (Mongoose)
- **AI Integration**: Groq SDK (Llama 3)
- **PDF Processing**: PDF-Parse
- **Authentication**: JSON Web Tokens (JWT) & Bcrypt
- **File Handling**: Multer

---

## 📂 Project Structure

```bash
AI-Learning-Assistant/
├── backend/                # Node.js/Express Backend
│   ├── config/             # DB & Env Config
│   ├── controllers/        # Route Logic (Auth, Document, AI, Payment)
│   ├── middleware/         # Auth & Error Handling Middleware
│   ├── models/             # Mongoose Models (User, Document, Flashcard, etc.)
│   ├── routes/             # API Routes
│   ├── services/           # Business Logic (Subscription limits, etc.)
│   ├── uploads/            # Local storage for uploaded PDFs
│   └── server.js           # Entry point
│
├── frontend/               # React Frontend
│   ├── src/
│   │   ├── assets/         # Static Assets
│   │   ├── components/     # Reusable UI Components (Auth, Layout, Common)
│   │   ├── context/        # Global State (AuthContext, ThemeContext)
│   │   ├── pages/          # Application Pages (Dashboard, Documents, Profile)
│   │   ├── services/       # API Service Functions
│   │   └── utils/          # Helpers (Axios Instance)
│   └── package.json
│
└── README.md               # Project Documentation
```

---

## 🔧 Installation & Setup

### Prerequisites
- Node.js (v16+)
- MongoDB (Local or Atlas URI)
- Groq API Key (for AI features)

### 1. Clone the Repository
```bash
git clone <repository-url>
cd AI-Learning-Assistant
```

### 2. Backend Setup
Navigate to the backend folder and install dependencies:
```bash
cd backend
npm install
```

Create a `.env` file in the `backend/` directory:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
GROQ_API_KEY=your_groq_api_key
client_url=http://localhost:5173
```

Start the backend server:
```bash
npm run dev
```

### 3. Frontend Setup
Open a new terminal, navigate to the frontend folder, and install dependencies:
```bash
cd frontend
npm install
```

Start the frontend development server:
```bash
npm run dev
```

### 4. Access the App
Open your browser and navigate to:
```
http://localhost:5173
```

---

Made with ❤️ by the Patel Divyanshu .M. .
# LearnifyAI---AI-Learning-Assistant-
