# Blogging-chat

A full-stack **Blogging and Chat application** built with **Node.js**, **Express**, **MongoDB**, and **EJS**.

This project provides users with a platform to write blog posts, comment on posts, and chat in real-time (or via simple messaging between users). It uses authentication with **JWT**, secure password hashing with **bcrypt**, and dynamic server-rendered pages with **EJS**.

## 🚀 Features

✅ User signup and login with JWT authentication  
✅ Create, edit, delete blog posts  
✅ Comment system for posts  
✅ Chat functionality between users (or real-time chat interface placeholder)  
✅ Secure password hashing with bcrypt  
✅ EJS for server-rendered views  
✅ Express routing and middleware  
✅ MongoDB database with Mongoose schemas

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Node.js | JavaScript runtime |
| Express | Server framework |
| MongoDB + Mongoose | Database |
| EJS | Templating engine |
| bcrypt | Password hashing |
| JSON Web Tokens | Authentication |
| Nodemon | Developer tooling |

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/AmanThakur100/Blogging-chat.git

2. **Install dependencies**

    npm install

3. **Create .env file**
Add:
PORT=3000
MONGODB_URI=<your_mongodb_connection_string>
JWT_SECRET=<your_jwt_secret>

Run the app

npm run dev

Visit http://localhost:3000 in your browser

📁 Project Structure
Blogging-chat/
├── models/                  # Database schemas (User, Post, Chat, etc.)
├── views/                   # EJS templates for UI pages
├── public/                  # Static files (CSS, JS, images)
├── app.js                   # Main server setup
├── package.json             # Project metadata & dependencies
├── .gitignore               # Ignored files
└── README.md                # You are here 😄
💡 Future Enhancements

✨ Real-time chat with Socket.io
✨ Like/dislike posts
✨ User profiles with avatars
✨ Notifications for new comments/messages
✨ Responsive UI with Bootstrap/Tailwind

📌 Contributions

Feel free to open issues or submit pull requests!
This project is open source and welcomes improvements 🙌

🧑‍💻 Author

Aman Thakur
💻 Developer | Open-Source Enthusiast
