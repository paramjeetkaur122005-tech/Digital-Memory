# 📓 Digital Diary

A modern and secure **MERN Stack Journaling Application** built to help users capture thoughts, track emotions, and preserve memories in a clean, distraction-free environment.

---

## 📸 Preview



<img width="1917" height="906" alt="image" src="https://github.com/user-attachments/assets/1e68ef8b-20f3-4680-8185-a3cb9ea34cec" />
<img width="1919" height="899" alt="image" src="https://github.com/user-attachments/assets/0abe3c46-7e14-41dc-ae3c-4a0a95559bdc" />



---

# 🌟 Key Features

### 🔐 Secure Authentication
- JWT-based authentication
- Password hashing using **Bcrypt.js**
- Protected private routes

### ✍️ Rich Text Journal Editor
Create beautifully formatted diary entries using **React Quill** with:
- Bold & Italic Text
- Bullet Lists
- Headings
- Embedded Images

### 😊 Mood Tracking
Track emotional patterns by tagging entries with moods such as:
- Happy
- Productive
- Stressed
- Motivated
- Calm

### ☁️ Media Upload Support
Upload and manage diary images securely using **Cloudinary** integration.

### 🔎 Smart Search & Filters
Quickly find memories through:
- Keyword search
- Date filters
- Mood filters

### 🌙 Minimal & Responsive UI
Built with:
- Tailwind CSS
- Responsive layouts
- Clean modern design
- Dark mode support

---

# 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| **Frontend** | React.js, Tailwind CSS |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB, Mongoose |
| **Authentication** | JWT, Bcrypt.js |
| **State Management** | Redux Toolkit |
| **Editor** | React Quill |
| **Cloud Storage** | Cloudinary |

---

# 📂 Project Structure

```text
digital-diary/
│
├── client/                         # React Frontend
│   ├── src/
│   │   ├── components/             # Navbar, Editor, Cards
│   │   ├── pages/                  # Home, Login, Register
│   │   ├── store/                  # Redux Toolkit Store
│   │   ├── hooks/                  # Custom Hooks
│   │   └── utils/                  # Utility Functions
│
├── server/                         # Express Backend
│   ├── models/                     # User & Journal Schemas
│   ├── routes/                     # Auth & Journal APIs
│   ├── controllers/                # Business Logic
│   ├── middleware/                 # JWT Verification
│   └── config/                     # Database & Cloudinary Config
│
└── README.md
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/digital-diary.git
cd digital-diary
```

---

# 🖥️ Backend Setup

Navigate to the backend folder:

```bash
cd server
```

Install dependencies:

```bash
npm install
```

Create a `.env` file inside the `server` directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_URL=your_cloudinary_url
```

Start the backend server:

```bash
npm start
```

Backend runs on:

```bash
http://localhost:5000
```

---

# 🌐 Frontend Setup

Open a new terminal and navigate to the client folder:

```bash
cd client
```

Install dependencies:

```bash
npm install
```

Start the frontend application:

```bash
npm start
```

Frontend runs on:

```bash
http://localhost:3000
```

---

# 🛡️ Security Features

- HTTP-only Cookies for enhanced security
- Protected API routes using JWT middleware
- Password encryption using Bcrypt.js
- Secure environment variable handling
- Private route guards for authenticated users

---

# 📈 Future Enhancements

- [ ] AI-based mood analysis
- [ ] Voice-to-text journaling
- [ ] Calendar heatmap visualization
- [ ] End-to-end encrypted entries
- [ ] Export journal entries as PDF
- [ ] Reminder notifications

---

# 🤝 Contributing

Contributions are welcome.

### Steps to contribute:

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature/AmazingFeature
```

3. Commit your changes

```bash
git commit -m "Added AmazingFeature"
```

4. Push your branch

```bash
git push origin feature/AmazingFeature
```

5. Open a Pull Request

---

# 📜 License

Licensed under the **MIT License**.

---

# ❤️ Developed by Paramjeet

*"Some memories fade. The important ones deserve a home."*
